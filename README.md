# abm-study-group-4

<!-- badges: start -->
[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
[![License: GPLv3](https://img.shields.io/badge/license-GPLv3-bd0000.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
<!-- badges: end -->

## Overview

This repository contains the slides from the presentation _Patterns for Model Structure_, delivered on August 13, 2025, at the [Agent-Based Model Study Group](https://github.com/abmstudygroup). The slides are available [here](https://danielvartan.github.io/abm-study-group-pres-4/).

## How to Use

This presentation was created using the [Quarto](https://quarto.org/) publishing system and the [R](https://www.r-project.org/) programming language. To build the slides locally, you will need to have these tools installed on your computer.

The [`renv`](https://rstudio.github.io/renv/) R package is used to manage the R package dependencies. To install the required packages, run the following commands in your R console before rendering the slides:

```r
# install.packages("renv")
renv::restore()
```

After installing the dependencies, you can render the slides by executing the following command at the project root directory in your terminal:

```bash
quarto render
```

This will generate the slides in the `docs` directory.

## How to Cite

To cite this work, please use the following format:

Vartanian, D. (2025). *Patterns for model structure* \[Presentation\].
<https://danielvartan.github.io/abm-study-group-pres-4>

A BibTeX entry for LaTeX users is:

``` latex
@Misc{vartanian2025,
  title = {Patterns for model structure},
  author = {{Daniel Vartanian}},
  year = {2025},
  url = {https://danielvartan.github.io/abm-study-group-pres-4},
  langid = {en},
  note = {Presentation}
}
```

## License

[![License: GPLv3](https://img.shields.io/badge/license-GPLv3-bd0000.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

The code in this repository is licensed under the [GNU General Public License Version 3](https://www.gnu.org/licenses/gpl-3.0), while the presentation is available under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

``` text
Copyright (C) 2025 Daniel Vartanian

The code in this repository is free software: you can redistribute it and/or
modify it under the terms of the GNU General Public License as published by the
Free Software Foundation, either version 3 of the License, or (at your option)
any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program. If not, see <https://www.gnu.org/licenses/>.
```
