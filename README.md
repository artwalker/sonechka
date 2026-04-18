# Sonechka · Release Binaries and Docs

Sonechka is a proprietary, local-first CLI agent. This public repository is the binary distribution and documentation portal only.

## ⚠️ PROPRIETARY SOFTWARE — NOT OPEN SOURCE
This repository contains official binaries and documentation only. The source code is proprietary and confidential. Unauthorized use, distribution, or reverse engineering is strictly prohibited.

## Download

Pre-built binaries for Linux, macOS, and Windows are available on the [Releases](https://github.com/artwalker/sonechka/releases) page.

Each release includes:

- platform archives
- `SHA256SUMS.txt` for integrity verification
- the same operator-facing product surface documented in the public docs

## Documentation

The published documentation site lives at <https://artwalker.github.io/sonechka/>.

Recommended first-run path:

```bash
codex login
sonechka setup codex --validate
sonechka auth status
sonechka chat --check --json --export-latest
sonechka chat
```

## License

Personal, non-commercial use is permitted. **All commercial use requires a paid license.** See [LICENSE](LICENSE) for full terms.

## Commercial Licensing

For enterprise deployment, white-label integration, or commercial use, contact: wxinxings@gmail.com

---
© 2026 Art Walker. All rights reserved.
