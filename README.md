# hyperliquid-rust-sdk

SDK for Hyperliquid API trading with Rust.

## Usage Examples

See `src/bin` for examples. You can run any example with `cargo run --bin [EXAMPLE]`.

## Installation

`cargo add hyperliquid_rust_sdk`

## Local qualification

Automatic pull-request and master-push CI is retired. Before merging source changes, merge the current default branch and run the existing build, formatting, Clippy and test script through the maintained admitted gate:

```bash
beelink-gate auto https://github.com/tangle-network/hyperliquid-rust-sdk.git <full-sha> -- bash ./ci.sh
```

The admitted host needs the repository-owned Rust toolchain and its rustfmt/Clippy components. The existing script builds before running tests. Workflow/documentation-only changes use YAML, actionlint and content/exact-diff checks. Qualification does not publish a crate or authorize funded API examples, account changes, or trading operations.

## License

This project is licensed under the terms of the `MIT` license. See [LICENSE](LICENSE.md) for more details.

```bibtex
@misc{hyperliquid-rust-sdk,
  author = {Hyperliquid},
  title = {SDK for Hyperliquid API trading with Rust.},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/hyperliquid-dex/hyperliquid-rust-sdk}}
}
```
