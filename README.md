# ConTeXt docker image

This repository provides dockerfiles for ConTeXt distribution (full
installation with all modules). It also provides the necessary tooling to
execute common helper tools (e.g. vim for syntax highlighting).

Please note that we only provide the ConTeXt releases MkIV (Current and Beta)
and LMTX.

To use one of these images in your projects, simply lookup the name of
the image and use

    FROM registry.gitlab.com/islandoftex/images/context:beta

or any other tag.
