# CV

Bilingual CV (English / Turkish) built with LaTeX, deployed via GitHub Actions.

**[beyenilmez.github.io/cv](https://beyenilmez.github.io/cv)**

| Language | PDF |
|----------|-----|
| English | [en/bedirhan_yenilmez_cv.pdf](https://beyenilmez.github.io/cv/en/bedirhan_yenilmez_cv.pdf) |
| Turkish | [tr/bedirhan_yenilmez_cv.pdf](https://beyenilmez.github.io/cv/tr/bedirhan_yenilmez_cv.pdf) |

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
