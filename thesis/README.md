# Master Thesis Template

This directory contains all the latex files that you will need to write your master thesis. Talk to your advisor about how to structure it, and how to break down content into chapters. Don't forget to consult [Jennifer Widom's writing tips](https://cs.stanford.edu/people/widom/paper-writing.html). 


## Building
Simply execute `make all` in order to build the thesis. `make all` might run slow, as it tries to find references and build the bibliography. Run `make` in case you did not add any references since the last build.

## Cleaning Up
In case you run into weird problems, try to `make clean` in order to delete any temporary files that are required by latex.
