# DxcMacros

> **Note:** This crate is a supporting internal macro crate for [`dxc`](https://github.com/efahnjoe/dxc). It is not intended for direct use.

Due to Rust's macro system limitations, `dxc-macros` is published as a separate crate to enable procedural macro expansion during the compilation, building, and packaging of the main [`dxc`](https://github.com/efahnjoe/dxc) library.

## Important Notes

- **Do not install or depend on `dxc-macros` directly via Cargo.**
  It is designed solely for internal use by `dxc` and does not follow the same versioning scheme.
- This README intentionally omits detailed documentation, API references, or usage examples for `dxc-macros`.
  Such details may be disclosed publicly in the future, but are currently considered implementation internals.
- End users should interact only with the main [`dxc`](https://github.com/efahnjoe/dxc) crate.

## Support & Feedback

We sincerely appreciate your support and understanding!

If you encounter any issues related to this crate (e.g., build failures when using `dxc`), please:

- Open an issue at: https://github.com/efahnjoe/dxc-macros/issues
- Or start a discussion at: https://github.com/efahnjoe/dxc-macros/discussions

## Contributing

If you'd like to contribute, please ensure you have carefully read our contribution guidelines in
[`CONTRIBUTING`](./.github/CONTRIBUTING.md) before submitting a pull request.

Thank you for being part of the DXC community!

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
