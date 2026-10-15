# Changelog

## Unreleased

- ZSTD now honors nonzero `Options.CompressionLevel` values, which were previously ignored. Applications that already set a nonzero level may see different compression speed and ratios. Zero preserves the default ZSTD preset (level 3).
