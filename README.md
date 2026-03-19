# ijq-m0x41

[![ijq-m0x41](https://snapcraft.io/ijq-m0x41/badge.svg)](https://snapcraft.io/ijq-m0x41)

This repository defines an "unofficial" _Snapcraft_ `snap` package for `ijq` of [gpanders/ijq](https://sr.ht/~gpanders/ijq/). The `snapcraft.yaml` builds the application from source, includes `jq` and makes it available as a `snap` package with the name `ijq-m0x41` from the _Snapcraft_ store.

To install:

```bash
# Install
sudo snap install ijq-m0x41

# Define alias for convenience
sudo snap alias ijq-m0x41.ijq ijq

# Test
echo '{"name":"John", "age":30, "car":null}' | ijq
```

## License & Attribution

The source for `ijq` is release under the [GPLv3](https://git.sr.ht/~gpanders/ijq/tree/v1.0.0/item/README.md) and is attributed to [gpanders/ijq](https://sr.ht/~gpanders/ijq/).

This repository is also licensed under [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html) and covers the `snapcraft.yaml` definition. The subsequent build of `ijq` from official sources should be considered "unofficial" as not done by the original author.

## Upstream Projects

- **ijq**: [codeberg.org/gpanders/ijq](https://codeberg.org/gpanders/ijq) (originally [sr.ht/~gpanders/ijq](https://sr.ht/~gpanders/ijq/))
- **scdoc**: [git.sr.ht/~sircmpwn/scdoc](https://git.sr.ht/~sircmpwn/scdoc)
- **jq**: [github.com/jqlang/jq](https://github.com/jqlang/jq)

## Disclaimer

This `snap` is an unofficial, community-maintained package. It is provided "as is", without warranty of any kind. The maintainer of this repository accepts no liability for any issues arising from its use.

If you encounter problems with `ijq` itself, please note that I am not in a position to help — this repository only covers the `snap` packaging. The upstream maintainers may also be unable to assist, as `snap` is not an officially supported packaging format for `ijq`.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/ijq-m0x41)
