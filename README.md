# CV

Bilingual CV (English / Turkish) built with LaTeX, deployed via GitHub Actions.

**[cv.bedirhanyenilmez.com](https://cv.bedirhanyenilmez.com)**

| Language | PDF |
|----------|-----|
| English | [en/bedirhan_yenilmez_cv.pdf](https://cv.bedirhanyenilmez.com/en/bedirhan_yenilmez_cv.pdf) |
| Turkish | [tr/bedirhan_yenilmez_cv.pdf](https://cv.bedirhanyenilmez.com/tr/bedirhan_yenilmez_cv.pdf) |

## Local build

```bash
latexmk -pdf src/cv-en.tex
latexmk -pdf src/cv-tr.tex
```

Requires `latexmk` and TeX Live.

## Private version

Add a repository secret `PHONE_NUMBER`, then run the **Build Private CV** workflow.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more information.
