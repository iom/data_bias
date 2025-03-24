# Data & Bias

This is a quick project showing how to quickly automate the generation of a report from a survey.

The survey here is the one used in [Gapminder 2017 views of the World](https://upgrader.gapminder.org/t/2017-gapminder-test?tab=q). This survey was used in a data literacy workshop. The results were displayed to let participants realise the importance how biais in our perception of the world.

The questions were encoded in [xlsform](http://xlsform). Note that LLM are working quite nicely to quickly convert a series of questions to xlsform.

Once data are collected in kobotoolbox, using the form [data-raw/form.xls], we download the results within the same folder.

Here we use the [kobocruncher]() R package, to quickly format the results and the [iomdown](https://iom.github.io/iomdown/) PowerPoint template within the [Views_of_the_World.Rmd]() Rmarkdown.

The Result is a PowerPoint file [here]().

