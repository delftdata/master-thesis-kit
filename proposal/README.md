# Thesis Proposal Template

The proposal text is self-describing: simply build the main.tex file and follow the instructions in there. A great guide on how to write scientific text is offered by [Jennifer Widom](https://cs.stanford.edu/people/widom/paper-writing.html).

## Building
Simply execute `make all` in order to build the thesis. `make all` might run slow, as it tries to find references and build the bibliography. Run `make` in case you did not add any references since the last build.

## Cleaning Up
In case you run into weird problems, try to `make clean` in order to delete any temporary files that are required by latex.