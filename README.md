# Data & Bias

This is a quick project showing how to quickly automate the generation of a report from a survey.

The survey here is the one used in [Gapminder 2017 views of the World](https://upgrader.gapminder.org/t/2017-gapminder-test?tab=q). This survey was used in a data literacy workshop. The results were displayed to let participants realize the importance how bias in our perception of the world.

The questions were encoded in [XlsForm](http://xlsform). Note that LLM are working quite nicely to quickly convert a series of questions to XlsForm.

Once data are collected in [kobotoolbox](https://kf.kobo.iom.int/), using the form [data-raw/form.xls](https://github.com/iom/data_bias/raw/refs/heads/main/data-raw/form.xlsx), we download the results within the same folder.

Here we use the [kobocruncher](https://edouard-legoupil.github.io/kobocruncher/) R package, to quickly format the results and the [iomdown](https://iom.github.io/iomdown/) PowerPoint template within the [Views_of_the_World.Rmd](https://github.com/iom/data_bias/blob/main/Views_of_the_World.Rmd) Rmarkdown.

The Result is a PowerPoint file [here](https://github.com/iom/data_bias/raw/refs/heads/main/Views_of_the_World.pptx).

