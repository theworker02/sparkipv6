<p align="center">
  <img src="docs/logo.svg" alt="sparkipv6 logo" width="128" height="128">
</p>

# sparkipv6

<p align="center">
  <strong>Spark validation gates for ipv6 inputs before they hit prod.</strong>
</p>

<p align="center">
  <a href="https://theworker02.github.io/sparkipv6/"><img src="https://img.shields.io/badge/docs-live-0B1F33?style=for-the-badge&labelColor=C9A227" alt="Docs"></a>
  <a href="https://github.com/theworker02/sparkipv6/releases/tag/v1.0.0"><img src="https://img.shields.io/badge/release-v1.0.0-success?style=for-the-badge" alt="Release"></a>
  <a href="https://github.com/theworker02/sparkipv6/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue?style=for-the-badge" alt="License"></a>
  <img src="https://img.shields.io/badge/node-%3E%3D18-informational?style=for-the-badge" alt="Node">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-0B1F33.svg" alt="version">
  <img src="https://img.shields.io/badge/category-validate-C9A227.svg" alt="category">
  <img src="https://img.shields.io/badge/deps-zero-brightgreen.svg" alt="deps">
  <img src="https://img.shields.io/badge/pages-enabled-222.svg" alt="pages">
</p>

## Why this exists

`sparkipv6` is a purpose-built `validate` toolkit: Spark validation gates for ipv6 inputs before they hit prod.

- Zero runtime dependencies
- Library API + stdin-friendly CLI
- Local-first (no network, no telemetry)
- Docs site on GitHub Pages

## Quick start

```bash
git clone https://github.com/theworker02/sparkipv6.git
cd sparkipv6
node --test
node src/cli.js
```

Live docs: **[https://theworker02.github.io/sparkipv6/](https://theworker02.github.io/sparkipv6/)**

## API

| Area | Path |
| --- | --- |
| Library | [`src/index.js`](./src/index.js) |
| CLI | [`src/cli.js`](./src/cli.js) |
| Tests | [`src/index.test.js`](./src/index.test.js) |

Category: `validate` · Release line: `v1.0.0`

## Documentation

- [CHANGELOG.md](./CHANGELOG.md) — release history
- [ACQUISITION.md](./ACQUISITION.md) — diligence brief
- [CONTRIBUTING.md](./CONTRIBUTING.md) · [SUPPORT.md](./SUPPORT.md) · [SECURITY.md](./SECURITY.md)

## License

MIT — see [LICENSE](./LICENSE).

<p align="center"><img src="docs/logo.svg" width="48" alt="sparkipv6"><br><sub>sparkipv6 · v1.0.0 · MIT</sub></p>
