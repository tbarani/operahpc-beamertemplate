A repository storing a beamer template to build presentations based on the [OperaHPC](https://www.operahpc.eu/) Euratom project template.

To generate a pdf presentation with [pandoc](https://pandoc.org/), one can use the provided example (file `example.md`) with the following command

```bash
pandoc example.md -f markdown+tex_math_single_backslash -t beamer -o presentation.pdf --pdf-engine=xelatex --syntax-highlighting=tango
```

[![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
