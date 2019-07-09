Merlin for OCaml 4.10 at the commit used for flambda2.0-stable

```
opam repository add flambda2-tools git+https://github.com/chambart/opam-repo-flambda2-tools.git
opam repository add beta git+https://github.com/ocaml/ocaml-beta-repository.git
opam switch install build-flamdba --repositories="default,beta,flambda2-tools" --package ocaml-variants.4.10.0+build-flambda2
opam install dune merlin
```