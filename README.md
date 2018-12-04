
# C++ Style Guide

This document describes recommended coding standard for writing C++ programs.
It is developed as additional learning material for [Informatik fur Mathematiker und Physiker](https://lec.inf.ethz.ch/ifmp/2018/) course taught at [ETH Zurich](https://www.inf.ethz.ch/).


# Usage

## Installation

The site is built on [Jekyll](https://jekyllrb.com/), a static site generator.

### GitHub
No installation is required. After a commit, GitHub should re-generate the site (usually in under a minute, but it may take up to 5 minutes).

### Locally
To setup on your local machine, follow the Jekyll [docs](https://jekyllrb.com/docs/).
After the successful build, a static version of the website should be located in `_site` directory.

## Adding Style Guidelines

To add a new guide add a file in the folder `_guidelines`.
Note, no other changes are required -- once the file is added it is automatically included in the list of guidelines on the main page.
The order of the guidelines shown on the main page is determined by the `date` attribute of the guideline. 

When adding new rules try to include simple examples that illustrate the difference between how the code should and should not be written.

## Referencing Guidelines

Each guideline is also generated as a separate html page which can be linked to.


# Change Log
Current Version 0.90

- Added set of style guides. Author: Pavol Bielik
- Created initial template of the website and style guides. Author: Pavol Bielik
