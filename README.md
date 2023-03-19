# Dev Container Features

## Contents

- [d2](https://github.com/ksh5022/devcontainer-features/blob/main/src/d2/README.md)

## Usage

To use the features from this repository, add the desired features to devcontainer.json.

```json
{
    "image": "mcr.microsoft.com/devcontainers/base:debian",
    "features": {
        "ghcr.io/ksh5022/devcontainer-features/d2:1": {
            "version": "latest"
        }
    }
}
```
