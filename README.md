# flows-cli-builder

[![Release](https://img.shields.io/github/v/release/DadaDaMotha/flows-cli-builder)](https://img.shields.io/github/v/release/DadaDaMotha/flows-cli-builder)
[![Build status](https://img.shields.io/github/actions/workflow/status/DadaDaMotha/flows-cli-builder/main.yml?branch=main)](https://github.com/DadaDaMotha/flows-cli-builder/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/DadaDaMotha/flows-cli-builder/branch/main/graph/badge.svg)](https://codecov.io/gh/DadaDaMotha/flows-cli-builder)
[![Commit activity](https://img.shields.io/github/commit-activity/m/DadaDaMotha/flows-cli-builder)](https://img.shields.io/github/commit-activity/m/DadaDaMotha/flows-cli-builder)
[![License](https://img.shields.io/github/license/DadaDaMotha/flows-cli-builder)](https://img.shields.io/github/license/DadaDaMotha/flows-cli-builder)

Cli prompting tool for nested pydantic models

- **Github repository**: <https://github.com/DadaDaMotha/flows-cli-builder/>
- **Documentation** <https://DadaDaMotha.github.io/flows-cli-builder/>

## Installation from git

Install package from git:

    # Using poetry
    poetry add git+https://github.com/DadaDaMotha/flows-cli-builder.git#main

## Development

Install the environment and the pre-commit hooks with

```bash
make install
```

Run `make` to see all the options.

## Releasing a new version


Check release:

    bumpversion <major,minor,patch> --dry-run --allow-dirty --verbose

Then push the changes:

    git push && git push --tags
