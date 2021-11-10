# asdf-helmfile
![GitHub Actions Status](https://github.com/nwiizo/asdf-helmfile/workflows/Test/badge.svg?branch=main)

[Helmfile](https://github.com/roboll/helmfile) plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```
asdf plugin-add helmfile https://github.com//asdf-helmfile.git
```

## Use

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions.

### Environment Variable Options
- ASDF_HASHICORP_OVERWRITE_ARCH: force the plugin to use a specified processor architecture rather than the automatically detected value. Useful, for example, for allowing users on M1 Macs to install `amd64` binaries when there's no `arm64` binary available.
```
ASDF_HASHICORP_OVERWRITE_ARCH=amd64 asdf install helmfile latest
```
