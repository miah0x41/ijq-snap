# ijq-m0x41
[![ijq-m0x41](https://snapcraft.io/ijq-m0x41/badge.svg)](https://snapcraft.io/ijq-m0x41)

This repository defines an "unofficial" Snapcraft `snap` package for `ijq` of [gpanders/ijq](https://sr.ht/~gpanders/ijq/).  The `snapcraft.yaml` builds the application from source, includes `jq` and makes it available as a `snap` package with the name `ijq-m0x41` from the Snapcraft store. 

The steps undertaken to build the package will be subject to a blog post.

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
The source for `ijq` is release under the [GPLv3](https://git.sr.ht/~gpanders/ijq/tree/v0.3.8/item/README.md) and is attruibuted to [gpanders/ijq](https://sr.ht/~gpanders/ijq/).

This repository is also licensed under [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html) and covers the `snapcraft.yaml` definition.  The subsequent build of `ijq` from official sources should be considered "unofficial" as not done by the original author.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/ijq-m0x41)
