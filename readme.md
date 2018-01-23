## Shiny Workshop For PDX Rlang Meetup

Welcome to the workshop! We'll introduce you to the basics behind Shiny, an easy to use web application framework. We'll learn the basics by building a data exploration app piece by piece.

01) Getting the basics down
02) What are reactives for?
03) Tooltips and graph interactivity
04) Observe/isolate/update
05) Where to go next

## Requirements

You will need a laptop with RStudio installed. Additionally, you will need the following packages installed:

```
install.packages("fivethirtyeight", "shiny", "tidyverse")
```

If you want to use `plotly` in part 03, you'll also need to do this:

```
install.packages(c("devtools", "plotly"))
library(devtools)
install_github("hadley/ggplot2")
```

## Getting Started

Open up the tutorial at http://laderast.github.io/shiny_workshop_pdxrlang. There's more info on getting started in there.
