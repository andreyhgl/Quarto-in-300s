![Render Quarto presentation](https://github.com/andreyhgl/Quarto-in-300s/actions/workflows/publish.yml/badge.svg)

# README

This repo holds the code for a Quarto presentation: **Quarto in 300 seconds**.

> [!NOTE]
> Each push to this repo renders the presentation, which is hosted by github, [link](https://andreyhgl.github.io/Quarto-in-300s/).

## Installing Quarto

Follow the install guide [here](https://quarto.org/docs/get-started/).

## Running Quarto

To locally, use `preview`. This will spin up a `localhost`-server

```sh
quarto preview quarto-in-300-seconds.qmd
```

`render` generates a HTML which can be shared with others

```sh
quarto render quarto-in-300-seconds.qmd
```