# Field

A high performance GUI to query & manage `PostgreSQL`, `MySQL`, `MongoDB`, `DuckDB` databases.

Built with **Rust**. Written in [GPUI](https://gpui.rs) with [GPUI Component](https://github.com/longbridge/gpui-component)

Inspired by [Zedis](https://github.com/vicanso/zedis) and [PGUI](https://github.com/duanebester/pgui)

<img src="https://github.com/CyberTianzun/Field/blob/master/images/v0.1.0-pre.png" />

## Download

[Releases](https://github.com/CyberTianzun/Field/releases)

## Features

### Blazing Fast

All UI elements are rendered on the GPU for buttery smooth performance.

### Cross-Platform

Powered by GPUI, Field delivers a consistent, native experience across **macOS**, **Windows**, and **Linux**.

## TODO

- [ ] Talk To Data (Chat Panel)
- [X] More database kinds
  - [X] Clickhouse
  - [X] LibSQL / Turso
  - [X] SurrealDB
  - [X] CockroachDB
  - [X] TiDB
- [ ] Enhance UI
  - [ ] Multiselect spreadsheets
  - [ ] LSP for Editor
  - [ ] Code Fold for Editor
  - [ ] Connection Group
  - [X] Auto save
- [X] SSL/TLS
- [X] SSH tunnel
- [ ] Database tool
  - [ ] Table dump
  - [ ] Database dump
- [ ] Enhance management
  - [ ] Query History
- [ ] Vector Query

## Change Logs

### 0.1.1

1. fix UI bug
2. fix update field bug for mongodb

### 0.1.4

1. reopen last opened files
2. record recent files

### 0.1.5

1. enhance mongodb `update` and `query`

### 0.1.6

1. support for SSH tunnel and SSL/TLS

### 0.1.7

1. support for Clickhouse
2. support for Sqlite/libsql/Turso
3. support for CockroachDB
4. support for TiDB

## Repo

Because many modifications have been made to gpui-component, the source code will be released in future.


