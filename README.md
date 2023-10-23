# Patricia Slides

Public facing homepage for Dr Ternes' slides collection.

## Repository Setup

This repository was based on [Sparrow0hawk/quarto-revealjs-template](https://github.com/Sparrow0hawk/quarto-revealjs-template).

This repository is used to publish a [RevealJS][revealJS-url] website that has been written in
[Quarto][quarto-url]. It includes a [GitHub Action][ghAction-url] which will convert
the Quarto source to HTML and publish them via [GitHub Pages][ghPages-url].

Its a useful way of making slides portable as they are then available via the URL and naturally the slides are version
controlled.

## Preview locally

You'll need a working quarto.  This can be installed from conda and you'll also want to install the theme extension:

```bash
conda create -n quarto -c conda-forge quarto
conda activate quarto
quarto install --no-prompt extension grantmcdermott/quarto-revealjs-clean
```

You can then preview this via:

```bash
quarto preview
```

## Publish Locally

You will need to run `quarto publish gh-pages` once locally before deploying this template.

<!-- links -->
[quarto-url]: https://patricia-ternes.github.io/
[revealJS-url]: https://revealjs.com/
[ghAction-url]: https://docs.github.com/en/actions
[ghPages-url]: https://pages.github.com/
