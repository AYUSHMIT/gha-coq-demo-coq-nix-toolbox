<!---
This file was generated from `meta.yml`, please do not edit manually.
Follow the instructions on https://github.com/coq-community/templates to regenerate.
--->
# gha-coq-demo-coq-nix-toolbox

[![Docker CI][docker-action-shield]][docker-action-link]
[![Nix CI][nix-action-shield]][nix-action-link]

[docker-action-shield]: https://github.com/erikmd/gha-coq-demo-coq-nix-toolbox/actions/workflows/docker-action.yml/badge.svg?branch=master
[docker-action-link]: https://github.com/erikmd/gha-coq-demo-coq-nix-toolbox/actions/workflows/docker-action.yml

[nix-action-shield]: https://github.com/erikmd/gha-coq-demo-coq-nix-toolbox/actions/workflows/nix-action.yml/badge.svg?branch=master
[nix-action-link]: https://github.com/erikmd/gha-coq-demo-coq-nix-toolbox/actions/workflows/nix-action.yml




Demo using GHA.

## Meta

- Author(s):
  - Erik Martin-Dorel (initial)
- License: [MIT](LICENSE)
- Compatible Coq versions: 8.19 or later
- Additional dependencies:
  - [MathComp](https://math-comp.github.io) 2.0 or later (`ssreflect` suffices)
- Coq namespace: `Demo`
- Related publication(s): none

## Building and installation instructions

To build and install manually, do:
``` shell
git clone https://github.com/erikmd/gha-coq-demo-coq-nix-toolbox.git
cd gha-coq-demo-coq-nix-toolbox
coq_makefile -f _CoqProject -o Makefile
make   # or make -j <number-of-cores-on-your-machine>
make install
```

## Documentation

coq-demo consists of one theory and one test file, using definitions
and lemmas from the coq-mathcomp-ssreflect library.
