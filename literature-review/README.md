# Literature Review Document Template

This directory contains all the latex files that you will need to write your literature review. Please read the instructions carefully below. The template we follow is the same as the one of the ACM COmputing Surveys journal. The original template (v.1.55) can be found at the [site of the ACM templates](https://www.acm.org/publications/authors/submissions).

## Building
Simply execute `make all` in order to build the thesis. `make all` might run slow, as it tries to find references and build the bibliography. Run `make` in case you did not add any references since the last build.

## Cleaning Up
In case you run into weird problems, try to `make clean` in order to delete any temporary files that are required by latex.