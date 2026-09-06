# Repositories

## `ores-wasm-loaders`

| Repo | Kind | What it is |
| --- | --- | --- |
| [`owl-interfaces`](https://github.com/ores-wasm-loaders/owl-interfaces) | interfaces | The manifest and lifecycle vocabulary: TypeSpec + JSON Schema peers, validator, registry projection. |
| [`owl-coordinator`](https://github.com/ores-wasm-loaders/owl-coordinator) | lib-core | Scheduling and lifecycle. Framework-independent. |
| [`owl-rust-loader`](https://github.com/ores-wasm-loaders/owl-rust-loader) | pub-lib-core | wasm-bindgen lifecycle + Leptos and Dioxus hooks. |
| [`owl-flutter-loader`](https://github.com/ores-wasm-loaders/owl-flutter-loader) | pub-lib-core | Flutter bootstrap lifecycle + embedded multi-view. |
| [`owl-manifest-tools.rs`](https://github.com/ores-wasm-loaders/owl-manifest-tools.rs) | cli | Generate and verify `owl-manifest.json`. Standard library only. |
| [`owl-e2e`](https://github.com/ores-wasm-loaders/owl-e2e) | e2e | Five entry paths, measured in bytes-after-click; hosting checks. |
| [`owl-infra`](https://github.com/ores-wasm-loaders/owl-infra) | infra | Content types, immutable release caching, scoped cross-origin isolation. |
| [`owl-docs`](https://github.com/ores-wasm-loaders/owl-docs) | docs | This documentation. |
| [`owl-monorepo`](https://github.com/ores-wasm-loaders/owl-monorepo) | monorepo | Submodules, zed composition, the org-wide composition check. |

## `ores-wasm-loaders-test`

| Repo | Kind | What it is |
| --- | --- | --- |
| [`owl-fixtures`](https://github.com/ores-wasm-loaders-test/owl-fixtures) | clients | Synthetic release trees, their manifests, and the shared test kit. |
| [`owl-conformance`](https://github.com/ores-wasm-loaders-test/owl-conformance) | e2e | The adapter conformance suite, on this org's Actions minutes. |
