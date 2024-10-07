# Workshop presentations

Please publish your presentation materials in a repo that you create in our workshop organization at https://github.com/intro-to-data-science-24-workshop. There's a naming convention for the repos, which should indicate the workshop number (see below), your name (one group member only), and a very brief description, all lowercase and separated by dashes. E.g.: `01-topic-lastname1-lastname2-lastname3/`. For more information about your task, check out the document `workshop-guidelines.pdf` in this repository.

## R Markdown

Please make your presentations using [R Markdown](https://rmarkdown.rstudio.com/). You can use any one of the multiple slide deck options. (For what it's worth, I use the [xaringan package with a modified metropolis theme](https://github.com/yihui/xaringan/wiki/Themes) for my lecture slides). Or you can output as a [GitHub document](https://rmarkdown.rstudio.com/github_document_format.html) or [HTML document](https://bookdown.org/yihui/rmarkdown/html-document.html). If you choose the latter, I would request that you please include `keep_md: true` in your YAML, so that it is readable directly on GitHub.

## Recording

There are multiple ways to record your computer screen and voice for the presentation videos. You can [record a presentation on Zoom](https://www.youtube.com/watch?v=P6cTbnUPwfY), [record a presentation via MS Teams](https://www.youtube.com/watch?v=ymnTVklGtAY), or use [open source software OBS Studio](https://www.youtube.com/watch?v=jKgM18lOsr4). Just make sure the `format is mp4` and the entire thing is `no longer than 15 minutes`! If you need to convert between video formats, I recommend the open source video transcoder [HandBrake](https://handbrake.fr/). For minimal cutting you might want to use lightweight [LosslessCut](https://github.com/mifi/lossless-cut).


## Topics

Topics will be randomly allocated to groups of 2-3 students. You can divide main responsibilities as long as the workload is distributed in a fair manner. If the statement of contributions puts that into question, I will follow up. Freeriding at the expense of other team members will not be tolerated.

| Workshop | Focus | Topic | Resources | 
|---------|-------|-----------|-----------|
| 01 | Wrangling | Clean data and tabyls with janitor| [a](https://sfirke.github.io/janitor/index.html), [b](https://sfirke.github.io/janitor/articles/tabyls.html) |
| 02 | Wrangling | Working with factors and labels | [a](https://forcats.tidyverse.org/), [b](https://strengejacke.github.io/sjlabelled/articles/intro_sjlabelled.html) |
| 04 | Wrangling | Advanced string processing with stringi | [a](https://stringi.gagolewski.com/), [b](https://www.jstatsoft.org/article/view/v103i02) |
| 03 | Wrangling | Dates and times with lubridate | [a](https://lubridate.tidyverse.org/), [b](https://r4ds.hadley.nz/datetimes) |
| 03 | Web data | Dynamic web data collection with senelider | [a](https://ashbythorpe.github.io/selenider/), [b](https://r-datacollection.com/) |
| 03 | Web data | Creating web APIs with plumber | [a](https://www.rplumber.io/), [b](https://github.com/rstudio/cheatsheets/blob/main/plumber.pdf) |
| 05 | Analysis | Tidy tools for time-series data | [a](https://tsibble.tidyverts.org/), [b](https://tidyverts.org/) |
| 07 | Analysis | Geospatial analysis with sf | [a](https://r-spatial.github.io/sf/index.html), [b](https://pebesma.staff.ifgi.de/RJwrapper.pdf) |
| 08 | Visualization | Presentation-ready tables with gt and gtExtra | [a](https://gt.rstudio.com/), [b](https://jthomasmock.github.io/gtExtras/) |
| 10 | Visualization | Interactive graphics with plotly | [a](https://github.com/plotly/plotly.R), [b](https://plotly.com/r/) |
| 09 | Visualization | Interactive maps with leaflet | [a](https://rstudio.github.io/leaflet/), [b](https://leafletjs.com/index.html) |
| 11 | Workflow | Ensuring reproducibility with renv | [a](https://rstudio.github.io/renv/), [b](https://rstudio.github.io/renv/articles/renv.html) |
| 12 | Workflow | Tidy modeling with tidymodels | [a](https://www.tidymodels.org/), [b](https://www.tmwr.org/) |
| 12 | Workflow | Establishing pipelines with targets | [a](https://docs.ropensci.org/targets/), [b](https://books.ropensci.org/targets/) |
