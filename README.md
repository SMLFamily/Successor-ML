Successor ML
============

Successor ML is an effort to *evolve* the Standard ML language while keeping true
to its clean and elegant design.

A related effort is the evolution of the
[**Standard ML Basis Library**](https://github.com/SMLFamily/BasisLibrary).

Note that this repository used to be called `Proposed-Definition-of-Successor-ML`, but
it has been renamed to `Successor-ML`.  Github will automatically redirect the old URL,
but you can also updating any existing local clones using the command:
```sh
$ git remote set-url origin https://github.com/SMLFamily/Successor-ML.git
```

## Definition

The LaTeX sources for **The Definition of Successor ML** can be found in the
`definition` directory.

## Design proposals
*Coming soon*

## Implementation efforts

At this time, there are three implementation efforts to support Successor ML.

+ The most complete is Andreas Rossberg's [**HaMLet S**](https://www.mpi-sws.org/~rossberg/hamlet/)
  implementation, which implements all of the features described in the
  **The Definition of Successor ML** (and more).

+ The [**MLton**](https://mlton.org) implementation of Standard ML is working on supporting
  Successor ML features.  See [http://mlton.org/SuccessorML] for details.

+ The [**Standard ML of New Jersey**](https://smlnj.org) implementation of Standard ML
  is also working on supporting Successor ML features
  (as of [Version 110.79](http://smlnj.org/dist/working/110.79/110.79-README.html)).
