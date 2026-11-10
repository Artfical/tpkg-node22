# node22

Node.js 22.23.4 and npm 10.9.9 (the official linux-x64 build; 64-bit tOS)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install node22
```

| | |
|---|---|
| Version | 22.23.4 |
| Licence | MIT; npm Artistic-2.0 |
| Upstream | https://nodejs.org |
| Needs | none |
| Needs tOS build | 603 or newer |
| Size | 46429532 bytes (137779200 unpacked) |
| SHA-256 of the `.tpkg` | `d2951868c94b10b8d4e565bc2bfc69fb444dcfbba91585fc2a027ac1b56e91ad` |

## Commands it adds

| Command | Runs |
|---|---|
| `node` | `bin/node` |
| `npm` | `lib/node_modules/npm/bin/npm-cli.js` |
| `npx` | `lib/node_modules/npm/bin/npx-cli.js` |

## Download

The package file (`node22-22.23.4.tpkg`) and the sources it was built from are the assets of the
[v22.23.4 release](https://github.com/Artfical/tpkg-node22/releases/tag/v22.23.4).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- (none: see the upstream page above)

Check a download: `sha256sum node22-22.23.4.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: MIT; npm Artistic-2.0. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
