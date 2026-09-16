# Does AI help us think?

PSYCH3023 (PRE 2026) in-class research project. A Quarto website reporting a
student study on AI use, metacognition and critical thinking, written for a
high school audience.

## Render locally

Install [Quarto](https://quarto.org/docs/get-started/), then from the
repository root:

```sh
quarto preview   # live preview in the browser while editing
quarto render    # writes the finished site to docs/
```

## Publish

1. Run `quarto render`.
2. Commit the `.qmd` sources **and** the `docs/` folder, then push to `main`.
3. In the GitHub repository go to **Settings › Pages** and set the source to
   **Deploy from a branch**, branch `main`, folder `/docs`.

## Layout

| Path | Content |
|---|---|
| `index.qmd` | Home page |
| `ideas/` | How AI changes thinking, Metacognition, Using AI well |
| `study/` | How we studied it, What we found, What it means |
| `do/` | For students, For schools |
| `whats-next.qmd` | Conclusions and future research |
| `about.qmd` | Team, references, AI use statement |
| `images/` | Figures exported from the analysis |
| `styles.scss` | Theme overrides on top of `cosmo` |
| `docs/` | Rendered site served by GitHub Pages |

Every page is a skeleton: each section holds one `TODO` line saying what
belongs there. Statistics may only come from the findings reference in the
project plan.

## Earlier working files

`Goals - 1`, `Rough Draft - 1` and `website basic outline` are notes from
the planning stage and are not part of the rendered site.
