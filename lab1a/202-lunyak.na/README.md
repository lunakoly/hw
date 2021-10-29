# Блокирующий TCP чат

Написан на Rust.
Работа проверялась на Windows и macOS.

Так как работа над чатом началась до появления данного репозитория, то ее можно найти [тут](https://github.com/lunakoly/RustNetCourse).

На данный момент, в этом репозитории находится пример с блокирующим сервером и неблокирующим клиентом. Таким образом код одновременно подходит под обе части лаб1.

## Протокол

Полное описание протокола находится в [README](https://github.com/lunakoly/RustNetCourse/blob/main/README.md).

## Build

Для сборки использовались `cargo` 1.55.0 (32da73ab1 2021-08-23), `rustc` 1.55.0 (c8dfcfe04 2021-09-06).

Сервер:

```sh
cd server
cargo build
```

Клиент:

```sh
cd client
cargo build
```

Советую предварительно запустить `./configure.sh`, чтобы он настроил симлинки на один единый `target/`.

## Запуск

Сервер:

```sh
cd server
cargo run
```

Клиент:

```sh
cd client
cargo run
```

Подробности запуска можно прочесть там же, в исходной репе.