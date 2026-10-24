# speedtest-cli

CLI-замер скорости интернета на Rust: download, upload, ping и jitter.

## Возможности (план)

- многопоточный замер download/upload (все ядра);
- замер latency и jitter;
- автоматический выбор сервера;
- цветной вывод: пинг, скорость, итоговая таблица;
- опция `--json` для машинной обработки.

## Стек

- Язык: Rust
- Планируемые библиотеки: `clap`, `tokio`, `reqwest`, `serde`, `serde_json`, `indicatif`

## Сборка и запуск

```bash
cargo build --release
cargo run --release
```

## Лицензия

MIT
