Gistr paper
===========

Latex source for our Gistr paper based on chapter 3 of my [thesis](https://github.com/wehlutyk/thesis).

Setup
-----

After you `git clone`, make sure you `git submodule update --init` to get the `analysis` submodule initialized and filled up (and don't use `--recursive` as we're not interested in the nested submodules inside `analysis`, which are many and heavy as I have somewhat abused of the tool).

Bibliography uses the Bibtex and Natbib.

If you have [Latexmk](https://www.ctan.org/pkg/latexmk/) installed, use `latexmk -pdf gistr-master.tex`.
