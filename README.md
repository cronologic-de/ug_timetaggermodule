# TimeTagger Module

Documentation for the cronologic **Modular Time-to-Digital converter**.

This is a Sphinx project that creates the online documentation for the
[TimeTagger-Module](https://www.cronologic.de/product/tdc-modules) by
[cronologic GmbH & Co. KG](https://www.cronologic.de).

## Prerequisites

Python is necessary for creating the HTML output.

Python and LuaLaTeX are necessary for creating the LaTeX/PDF output.

Dependencies are managed using [uv](https://docs.astral.sh/uv).

### Fonts for LaTeX

The `fontspec` package is used for the LaTeX output. It may complain that fonts
are missing from your system.

The following fonts are required for the LaTeX output and are included in the
listed packages.

- Montserrat (main font):
  [montserrat](https://ctan.org/tex-archive/fonts/montserrat)
- TeX Gyre Adventor (headings font): [tex-gyre](https://ctan.org/pkg/tex-gyre)
- Latin Modern Math (math font): [lm-math](https://ctan.org/pkg/lm-math)
- Latin Modern Mono Light (monospaced font): [lm](https://ctan.org/pkg/lm)
- KerkisSans (expanded Greek letters): [kerkis](https://ctan.org/pkg/kerkis)

## Building

Run

```shell
make html
```

or

```shell
make latexpdf
```

to compile the project as HTML or PDF. The HTML (PDF) output is in `build/html/`
(`build/latex/`).

Alternatively, if you do not have make, use the [make.bat](make.bat) script
instead.

## License

![Creative Commons by-nd 4.0](https://i.creativecommons.org/l/by-nd/4.0/88x31.png)

This documentation is licensed under the
[CC BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0/) license (see
[LICENSE](LICENSE)). You are free to copy and redistribute the material in any
medium or format for any purpose, even commercially unchanged if you give
appropriate credit to cronologic GmbH & Co. KG. A link to
[this repository](https://github.com/cronologic-de/ug_timetagger4) or the
[product page](https://www.cronologic.de/product/timetagger) is sufficient. If
you decide to contribute to this repository, you transfer non-exclusive but
unlimited rights to your edit to cronologic GmbH & Co. KG.

The file [extraplaceins.sty](extraplaceins.sty) is in the public domain.
