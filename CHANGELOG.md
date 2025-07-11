# 0.6.0

- Remove miniz dependency and replace with libz bindings (or optionally libz-rs) (#39)
- Update OTS to v0.9.2 (see [upstream ots 0.9.2 release notes]) (#40)
- Update LZ4 to v1.10.0 (#41)
- Use [brotli-decompressor] instead of vendoring brotli sources (#42)

[brotli-decompressor]: https://github.com/dropbox/rust-brotli-decompressor
[upstream ots 0.9.2 release notes]: https://github.com/khaledhosny/ots/releases/tag/v9.2.0

# 0.5.2

- Remove cmake dependency.
- Fix c++ stdlib detection for all targets by using `cc-rs`.

# 0.5.1

- Use correct c++ stdlib implementation on OpenHarmony OS.

# 0.5.0

- Fix a build issue on windows
- Update ots to v1.9.0
- Vendor ots and dependencies (brotli, lz4 and woff2)