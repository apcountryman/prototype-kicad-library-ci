# prototype-kicad-library-ci
[![CI](https://github.com/apcountryman/prototype-kicad-library-ci/actions/workflows/ci.yml/badge.svg)](https://github.com/apcountryman/prototype-kicad-library-ci/actions/workflows/ci.yml)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](CODE_OF_CONDUCT.md)

KiCad library GitHub Actions CI prototype.

## Obtaining the Source Code
HTTPS:
```shell
git clone --recurse-submodules https://github.com/apcountryman/prototype-kicad-library-ci.git
```
SSH:
```shell
git clone --recurse-submodules git@github.com:apcountryman/prototype-kicad-library-ci.git
```

## Usage
This repository's Git `pre-commit` hook script is the simplest way to test this project
during development.
See the `pre-commit` script's help text for usage details.
```shell
./git/hooks/pre-commit --help
```

Additional checks, such as static analysis, are performed by this project's GitHub Actions
CI workflow.

## Versioning
`prototype-kicad-library-ci` follows the [Abseil Live at Head
philosophy](https://abseil.io/about/philosophy).

## Workflow
`prototype-kicad-library-ci` uses the [GitHub
flow](https://guides.github.com/introduction/flow/) workflow.

## Git Hooks
To install this repository's Git hooks, execute the `install` script located in the
`git/hooks` directory.
See the `install` script's help text for usage details.
```shell
./git/hooks/install --help
```

## Code of Conduct
`prototype-kicad-library-ci` has adopted the Contributor Covenant 2.0 code of conduct.
For more information, [see the `CODE_OF_CONDUCT.md` file in this
repository](CODE_OF_CONDUCT.md).

## Contributing
If you are interested in contributing to `prototype-kicad-library-ci`, please [read the
`CONTRIBUTING.md` file in this repository](CONTRIBUTING.md).

## Authors
- Andrew Countryman
- Jay Lamb

## License
`prototype-kicad-library-ci` is licensed under the same terms as the official KiCad
libraries.
That is, `prototype-kicad-library-ci` is licensed under the Creative Commons CC-BY-SA 4.0
License, with the same exception used by the official KiCad libraries.
For more information, [see the `LICENSE.md` file in this repository](LICENSE.md).
