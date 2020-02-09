
# RStudio Adwaita Dark Theme <!-- <img src="figures/logo.png" align="right" width="120" /> -->

<!-- badges: start -->

<!-- badges: end -->

## Overview

Qt style sheet (Adwaita) for RStudio as well as custom editor theme
(Darkula).

## Installation

The Qt style sheet can be installed by running the `INSTALL` script or
by manually running

``` bash
sudo cp rstudio-gnome-dark.qss /usr/lib/rstudio/resources/stylesheets/rstudio-gnome-dark.qss
```

To install the custom editor theme, go in RStudio Global Options \>
Appearance and click on <kbd>Add…</kbd> and add DarkulaAdwaita.rstheme.

Alternatively, run the snippet in the RStudio console to install and
apply Darkula Adwaita:

``` r
rstudioapi::addTheme("https://raw.githubusercontent.com/aldomann/rstudio-adwaita-dark-theme/master/DarkulaAdwaita.rstheme", apply=TRUE, force=TRUE)
```
