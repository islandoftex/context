# ConTeXt docker image

This repository provides dockerfiles for the ConTeXt distribution (full
installation with all modules). It also provides the necessary tooling to
execute common helper tools (e.g. vim for syntax highlighting).

Please note that we only provide the ConTeXt releases MkIV (current and beta)
and LMTX.

To use one of these images in your projects, simply lookup the name of
the image and use

    FROM registry.gitlab.com/islandoftex/images/context:beta

or any other tag.

The three main tags are `current` (updated monthly), `beta` and `lmtx`
(updated weekly).

## Licensing

The software in terms of the MIT license are the Dockerfiles and test files
provided. This does not include the pre-built Docker images we provide. They
follow the redistribution conditions of the bundled software.
