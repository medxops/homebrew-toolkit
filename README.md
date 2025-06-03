# MedxOps Homebrew Toolkit Tap

This repository provides the official Homebrew tap for all MedxOps CLI tools, including [trazr-gen](https://github.com/medxops/trazr-gen) and future utilities.

## About

The `medxops/toolkit` tap makes it easy to install and update MedxOps open source tools on macOS and Linux using [Homebrew](https://brew.sh/).

## Available Tools

- **trazr-gen**
  - Generate OpenTelemetry logs, metrics, and traces for testing and observability pipelines.
  - [Project page & documentation](https://github.com/medxops/trazr-gen)

## Installation

First, add the MedxOps toolkit tap:

```sh
brew tap medxops/toolkit
```

Then install `trazr-gen`:

```sh
brew install trazr-gen
```

To upgrade:

```sh
brew upgrade trazr-gen
```

To uninstall:

```sh
brew uninstall trazr-gen
```

## Contributing

Want to add another MedxOps tool to this tap? Open an issue or pull request!

---
