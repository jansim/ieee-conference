
# IEEE Transactions Conference Template

Built on top of [`rticles::ieee_article()`](https://pkgs.rstudio.com/rticles/reference/ieee_article.html).

## Creating a New Article

To create a new article using this format:

```bash
quarto use template jansim/ieee-conference
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

*TODO*: Replace the `jansim` with your GitHub organization.

```bash
quarto add jansim/ieee-conference
```

Then, add the format to your document options:

```yaml
format:
  ieee-conference-pdf: default
```    

## Options

*TODO*: If your format has options that can be set via document metadata, describe them.

## Example

Here is the source code for a minimal sample document: [ieee-conference.qmd](ieee-conference.qmd) and the rendered output: [ieee-conference.pdf](ieee-conference.pdf).

Note that formatting is slightly off in the rendered PDF due to issues in a local LaTeX installation. Rendering the produced TeX-document on e.g. overleaf produces better output

