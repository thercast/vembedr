
<!-- README.md is generated from README.Rmd. Please edit that file -->
The functions in this package make it a little bit easier to embed hosted videos into your RMarkdown documents and Shiny apps.

Installation
------------

You may install the latest development version from github by:

``` r
if (packageVersion("devtools") < 1.6) {
  install.packages("devtools")
}
devtools::install_github("ijlyttle/vembedr")
```

Use
===

It's fairly simple, you just need the video id from either Vimeo or YouTube. In RMarkdown, you may wish to set the alignment of the code chunk.

``` r
embed_vimeo("45196609")
```

``` r
embed_youtube("dQw4w9WgXcQ")
```

Embedding does not work for the standard Github site, but it does for `gh-pages`.

Future work
===========

Both YouTube and Vimeo support the use of query parameters in the URL. Supporting this is the likely next step.

Code of Conduct
---------------

Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.
