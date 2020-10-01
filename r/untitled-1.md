# Tutorials for learning R

![](https://i2.wp.com/www.r-bloggers.com/wp-content/uploads/2015/12/image02.png?resize=578%2C246&ssl=1)

\[social4i size=”large” align=”float-right”\]

There are tons of resources to help you learn the different aspects of R, and as a beginner this can be overwhelming. It’s also a dynamic language and rapidly changing, so it’s important to keep up with the latest tools and technologies.

That’s why [R-bloggers](https://www.r-bloggers.com/) and [DataCamp](https://www.datacamp.com/?tap_a=5644-dce66f&tap_s=10907-287229) have worked together to bring you a learning path for R. Each section points you to relevant resources and tools to get you started and keep you engaged to continue learning. It’s a mix of materials ranging from documentation, online courses, books, and more.

Just like R, this learning path is a dynamic resource. We want to continually evolve and improve the resources to provide the best possible learning experience. So if you have suggestions for improvement please email [\[email protected\]](https://www.r-bloggers.com/cdn-cgi/l/email-protection#7206131e5c15131e1b1e1b32151f131b1e5c111d1f) with your feedback.

## Learning Path

[Getting started:  The basics of R]()

[Setting up your machine]()

[R packages]()

[Importing your data into R]()

[Data Manipulation]()

[Data Visualization]()

[Data Science & Machine Learning with R]()

[Reporting Results in R]()

[Learning advanced R topics in \(paid\) online courses]()

[Next steps]()

## Getting started:  The basics of R

[![image02](https://i0.wp.com/www.r-bloggers.com/wp-content/uploads/2015/12/image02-300x172.png?resize=300%2C172&ssl=1)](https://i2.wp.com/www.r-bloggers.com/wp-content/uploads/2015/12/image02.png?ssl=1)

The best way to learn R is by doing. In case you are just getting started with R, this [~~free~~ introduction to R tutorial](https://www.datacamp.com/courses/free-introduction-to-r/?tap_a=5644-dce66f&tap_s=10907-287229) by DataCamp \(the first chapter is free\) is a great resource as well the successor [Intermediate R programming](https://www.datacamp.com/courses/intermediate-r?tap_a=5644-dce66f&tap_s=10907-287229) \(subscription required\). Both courses teach you R programming and data science interactively, at your own pace, in the comfort of your browser. You get immediate feedback during exercises with helpful hints along the way so you don’t get stuck.

Another free online interactive learning tutorial for R is available by O’reilly’s code school website called [try R](http://tryr.codeschool.com/). An offline interactive learning resource is [swirl](http://swirlstats.com/), an R package that makes if fun and easy to become an R programmer. You can take a swirl course by \(i\) [installing the package in R](http://swirlstats.com/students.html), and \(ii\) selecting a course from the course library. If you want to start right away without needing to install anything you can also choose for the [online version of Swirl](https://www.datacamp.com/swirl-r-tutorial?tap_a=5644-dce66f&tap_s=10907-287229).

There are also some very good [MOOC](https://en.wikipedia.org/wiki/Massive_open_online_course)’s available on edX and Coursera that teach you the basics of R programming. On edX you can find [Introduction to R Programming](https://www.edx.org/course/introduction-r-programming-microsoft-dat204x-0) by Microsoft, an 8 hour course that focuses on the fundamentals and basic syntax of R. At Coursera there is the very popular [R Programming course by Johns Hopkins](https://www.coursera.org/course/rprog). Both are highly recommended!

If you instead prefer to learn R via a written tutorial or book there is plenty of choice. There is the [introduction to R manual by CRAN](https://cran.r-project.org/doc/manuals/R-intro.pdf), as well as some very accessible books like Jared Lander’s [R for Everyone](http://www.jaredlander.com/r-for-everyone/&) or [R in Action](https://www.manning.com/books/r-in-action) by Robert Kabacoff.

## Setting up your machine

You can [download a copy of R](https://cran.r-project.org/) from the Comprehensive R Archive Network \(CRAN\). There are binaries available for Linux, Mac and Windows.

Once R is installed you can choose to either work with the basic R console, or with an integrated development environment \(IDE\). [RStudio](https://www.rstudio.com/) is by far the most popular IDE for R and supports debugging, workspace management, plotting and much more \(make sure to check out the [RStudio shortcuts](https://support.rstudio.com/hc/en-us/articles/200711853-Keyboard-Shortcuts)\).

[![image05](https://i2.wp.com/www.r-bloggers.com/wp-content/uploads/2015/12/image05-300x105.png?resize=300%2C105&ssl=1)](https://i2.wp.com/www.r-bloggers.com/wp-content/uploads/2015/12/image05.png?ssl=1)

Next to RStudio you also have [Architect](http://www.openanalytics.eu/architect), and Eclipse-based IDE for R. If you prefer to work with a graphical user interface you can have a look at [R-commander](http://www.rcommander.com/)  \(aka as Rcmdr\), or [Deducer](http://www.deducer.org/pmwiki/pmwiki.php?n%3DMain.DeducerManual).

## R packages

[![image04](https://i2.wp.com/www.r-bloggers.com/wp-content/uploads/2015/12/image04.png?resize=234%2C212&ssl=1)](https://i2.wp.com/www.r-bloggers.com/wp-content/uploads/2015/12/image04.png?ssl=1)

[R packages](http://r-pkgs.had.co.nz/intro.html) are the fuel that drive the growth and popularity of R. R packages are bundles of code, data, documentation, and tests that are easy to share with others. Before you can use a package, you will first have to install it. Some packages, like the [base package](http://www.rdocumentation.org/packages/base?tap_a=5644-dce66f&tap_s=10907-287229), are automatically installed when you install R. Other packages, like for example the [ggplot2 package](https://cran.r-project.org/web/packages/ggplot2/index.html), won’t come with the bundled R installation but need to be installed.

Many \(but not all\) R packages are organized and available from [CRAN](https://cran.r-project.org/doc/FAQ/R-FAQ.html%23What-is-CRAN_003f), a network of servers around the world that store identical, up-to-date, versions of code and documentation for R. You can easily install these package from inside R, using the [install.packages function](http://www.rdocumentation.org/packages/utils/functions/install.packages?tap_a=5644-dce66f&tap_s=10907-287229). CRAN also maintains a set of[ ](https://cran.r-project.org/web/views/)[Task Views](https://cran.r-project.org/web/views/) that identify all the packages associated with a particular task such as for example [TimeSeries](https://cran.r-project.org/web/views/TimeSeries.html).

Next to CRAN you also have [bioconductor](https://www.bioconductor.org/) which has packages for the analysis of high-throughput genomic data, as well as for example the [github](https://github.com/) and [bitbucket](https://bitbucket.org/) repositories of R package developers. You can easily install packages from these repositories using the [devtools](https://cran.r-project.org/web/packages/devtools/index.html) package.

Finding a package can be hard, but luckily you can easily search packages from CRAN, github and bioconductor using [Rdocumentation](http://www.rdocumentation.org/?tap_a=5644-dce66f&tap_s=10907-287229), [inside-R](http://www.inside-r.org/packages), or you can have a look at this [quick list of useful R packages](https://support.rstudio.com/hc/en-us/articles/201057987-Quick-list-of-useful-R-packages).

To end, once you start working with R, you’ll quickly find out that R package dependencies can cause a lot of headaches. Once you get confronted with that issue, make sure to check out [packrat](https://rstudio.github.io/packrat/) \(see [video tutorial](https://www.rstudio.com/resources/webinars/managing-package-dependencies-in-r-with-packrat/)\) or [checkpoint](http://blog.revolutionanalytics.com/2014/10/introducing-rrt.html). When you’d need to update R, if you are using Windows, you can [use the updateR\(\) function](http://www.r-statistics.com/2013/03/updating-r-from-r-on-windows-using-the-installr-package/) from the [installr](https://cran.r-project.org/web/packages/installr/) package.

## Importing your data into R

The data you want to import into R can come in all sorts for formats: flat files, statistical software files, databases and web data.

[![image03](https://i2.wp.com/www.r-bloggers.com/wp-content/uploads/2015/12/image03-300x155.png?resize=300%2C155&ssl=1)](https://i0.wp.com/www.r-bloggers.com/wp-content/uploads/2015/12/image03.png?ssl=1)

Getting different types of data into R often requires a different approach to use. To learn more in general on how to get different data types into R you can check out this [online Importing Data into R tutorial](https://www.datacamp.com/courses/importing-data-into-r?tap_a=5644-dce66f&tap_s=10907-287229) \(subscription required\), [this post on data importing](http://blog.datacamp.com/r-data-import-tutorial/?tap_a=5644-dce66f&tap_s=10907-287229), or [this webinar](https://www.rstudio.com/resources/webinars/data-wrangling-with-r-and-rstudio/) by RStudio.

* [Flat files](https://en.wikipedia.org/wiki/Flat_file_database) are typically simple text files that contain table data. The standard distribution of R provides functionality to import these flat files into R as a data frame with functions such as [read.table\(\)](http://www.rdocumentation.org/packages/utils/functions/read.table/?tap_a=5644-dce66f&tap_s=10907-287229) and [read.csv\(\)](http://www.rdocumentation.org/packages/utils/functions/read.table/?tap_a=5644-dce66f&tap_s=10907-287229) from the utils package. Specific R packages to import flat files data are [readr](https://cran.r-project.org/web/packages/readr/index.html), a fast and very easy to use package that is less verbose as utils and multiple times faster \([more information](https://github.com/hadley/readr)\), and data.table’s [fread\(\)](http://www.rdocumentation.org/packages/data.table/functions/fread?tap_a=5644-dce66f&tap_s=10907-287229) function for importing and munging data into R \([using the fread function](https://www.r-bloggers.com/importing-data-into-r-part-two/)\).
* In case you want to get your excel files into R, it’s a good idea to have a look at the [readxl package](https://github.com/hadley/readxl). Alternatively, there is the[ gdata package](https://cran.r-project.org/web/packages/gdata/) which has function that supports the import of Excel data, and the [XLConnect](https://cran.r-project.org/web/packages/XLConnect/) package. The latter acts as a real bridge between Excel and R meaning you can do any action you could do within Excel but you do it from inside R. [Read more on importing your excel files into R](http://blog.datacamp.com/r-tutorial-read-excel-into-r/?tap_a=5644-dce66f&tap_s=10907-287229).
* Software packages such as SAS, STATA and SPSS use and produce their own file types. The [haven package](https://github.com/hadley/haven) by Hadley Wickham can deal with importing SAS, STATA and SPSS data files into R and is very easy to use. Alternatively there is the [foreign package](https://cran.r-project.org/web/packages/foreign/index.html), which is able to import not only SAS, STATA and SPSS files but also more exotic formats like Systat and Weka for example. It’s also able to export data again to various formats. \(Tip: if you’re switching from SAS,SPSS or STATA to R, check out [Bob Muenchen’s tutorial](https://www.datacamp.com/courses/r-for-sas-spss-and-stata-users-r-tutorial?tap_a=5644-dce66f&tap_s=10907-287229) \(subscription required\)\)
* The packages used to connect to and import from a relational database depend on the type of database you want to connect to. Suppose you want to connect to a MySQL database, you will need the [RMySQL](https://cran.r-project.org/web/packages/RMySQL/) package. Others are for example the [RpostgreSQL](https://cran.r-project.org/web/packages/RPostgreSQL) and [ROracle](https://cran.r-project.org/web/packages/ROracle/index.html) package.The R functions you can then use to access and manipulate the database, is specified in another R package called [DBI](https://cran.r-project.org/web/packages/DBI).
* If you want to harvest web data using R you need to connect R to resources online using API’s or through scraping with packages like [rvest](https://cran.r-project.org/web/packages/rvest/). To get started with all of this, there is [this great resource](http://blog.rolffredheim.com/2014/02/web-scraping-basics.html) freely available on the blog of Rolf Fredheim.

## Data Manipulation

Turning your raw data into well structured data is important for robust analysis, and to make data suitable for processing. R has many built-in functions for data processing, but they are not always that easy to use. Luckily, there are some great packages that can help you:

* The [tidyr package](https://cran.r-project.org/web/packages/tidyr) allows you to “tidy” your data. Tidy data is data where each column is a variable and each row an observation. As such, it turns your data into data that is easy to work with. [Check this excellent resource on how you can tidy your data using tidyr.](https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html)
* If you want to do string manipulation, you should learn about the [stringr](https://cran.r-project.org/web/packages/stringr) package. [The vignette](https://cran.r-project.org/web/packages/stringr/stringr.pdf) is very understandable, and full of useful examples to get you started.
* dplyr is a great package when working with data frame like objects \(in memory and out of memory\). It combines speed with a very intuitive syntax. To learn more on dplyr you can take [this data manipulation course](https://www.datacamp.com/courses/dplyr-data-manipulation?tap_a=5644-dce66f&tap_s=10907-287229) \(subscription required\) and check out[ this handy cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf).
* When performing heavy data wrangling tasks, the [data.table](https://cran.r-project.org/web/packages/data.table) package should be your “go-to”package. It’s blazingly fast, and once you get the hang of it’s syntax you will find yourself using data.table all the time. [Check this data analysis course](https://www.datacamp.com/courses/data-table-data-manipulation-r-tutorial/?tap_a=5644-dce66f&tap_s=10907-287229) \(subscription required\) to discover the ins and outs of data.table, and use [this cheat sheet as a reference](https://s3.amazonaws.com/assets.datacamp.com/img/blog/data+table+cheat+sheet.pdf?tap_a=5644-dce66f&tap_s=10907-287229).
* Chances are you find yourself working with times and dates at some point. This can be a painful process, but luckily [lubridate](https://cran.r-project.org/web/packages/lubridate) makes it a bit easier to work with. Check [it’s vignette](https://cran.r-project.org/web/packages/lubridate/vignettes/lubridate.html) to better understand how you can use lubridate in your day-to-day analysis.
* Base R has limited functionality to handle time series data. Fortunately, there are package like[ zoo](https://cran.r-project.org/web/packages/zoo), [xts](https://cran.r-project.org/web/packages/xts) and [quantmod](https://cran.r-project.org/web/packages/quantmod). [Take this tutorial by Eric Zivot](https://faculty.washington.edu/ezivot/econ424/Working%2520with%2520Time%2520Series%2520Data%2520in%2520R.pdf) to better understand how to use these packages, and how to work with time series data in R.

If you want to have a general overview of data manipulation with R, you can read more in the book [Data Manipulation with R](https://www.amazon.com/Data-Manipulation-Second-Jaynal-Abedin/dp/1785288814/ref%3Dsr_1_2?s%3Dbooks%26ie%3DUTF8%26qid%3D1449054042%26sr%3D1-2%26keywords%3Ddata%2Bmanipulation%2Bwith%2Br) or see the [Data Wrangling with R](https://www.rstudio.com/resources/webinars/data-wrangling-with-r-and-rstudio/) video by RStudio. In case you run into troubles with handling your data frames, check [15 easy solutions](http://blog.datacamp.com/15-easy-solutions-data-frame-problems-r/?tap_a=5644-dce66f&tap_s=10907-287229) to your data frame problems.

## Data Visualization

One of the things that make R such a great tool is its data visualizations capabilities. For performing visualizations in R, [ggplot2](https://cran.r-project.org/web/packages/ggplot2) is probably the most well known package and a must learn for beginners! You can find all relevant information to get you started with ggplot2 on[http://ggplot2.org/](http://ggplot2.org/) and make sure to check out the [cheatsheet](https://www.rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf) and the [upcomming book](https://github.com/hadley/ggplot2-book). Next to ggplot2, you also have packages such as [ggvis](https://ggvis.rstudio.com/) for interactive web graphics \(see[tutorial](https://www.datacamp.com/courses/ggvis-data-visualization-r-tutorial?tap_a=5644-dce66f&tap_s=10907-287229) \(subscription required\)\), [googleVis](https://github.com/mages/googleVis) to interface with google charts \(learn to re-create [this TED talk](https://www.ted.com/talks/hans_rosling_shows_the_best_stats_you_ve_ever_seen)\), [Plotly for R](https://plot.ly/r/), and many more. See [the task view](https://cran.r-project.org/web/views/Graphics.html) for some hidden gems, and if you have some issues with plotting your data [this post](http://blog.datacamp.com/15-questions-about-r-plots/?tap_a=5644-dce66f&tap_s=10907-287229) might help you out.

In R there is a whole task view dedicated to handling spatial data that allow you to create beautiful maps such as this famous one:

[![image01](https://i0.wp.com/www.r-bloggers.com/wp-content/uploads/2015/12/image01-300x150.png?resize=300%2C150&ssl=1)](https://i1.wp.com/www.r-bloggers.com/wp-content/uploads/2015/12/image01.png?ssl=1)

To get started look at for example a package such as [ggmap](https://cran.r-project.org/web/packages/ggmap/index.html), which allows you to visualize spatial data and models on top of static maps from sources such as Google Maps and Open Street Maps. Alternatively you can start playing around with [maptools](http://maptools/), [choroplethr](http://www.arilamstein.com/open-source/), and the [tmap package](https://cran.r-project.org/web/packages/tmap/vignettes/tmap-nutshell.html). If you need a great tutorial take this [Introduction to visualising spatial data in R](https://cran.r-project.org/doc/contrib/intro-spatial-rl.pdf).

You’ll often see that visualizations in R make use of all these magnificent color schemes that fit like a glove on the graph/map/… If you want to achieve this for your visualizations as well, then deepen yourself into the [RColorBrewer package](https://cran.r-project.org/web/packages/RColorBrewer) and [ColorBrewer](http://colorbrewer2.org/).

One of the latest visualizations tools in R is [HTML widgets](http://www.htmlwidgets.org/). HTML widgets work just like R plots but they create interactive web visualizations such as  dynamic maps \([leaflet](https://rstudio.github.io/leaflet/)\), time-series data charting \([dygraphs](https://rstudio.github.io/dygraphs/)\), and interactive tables \([DataTables](https://rstudio.github.io/DT/)\). There are some very [nice examples](http://www.htmlwidgets.org/showcase_leaflet.html) of HTML widgets in the wild, and [solid documentation](http://www.htmlwidgets.org/develop_intro.html) on how to create your own one \(not in a reading mode: [just watch this video](https://www.rstudio.com/resources/webinars/creating-javascript-data-visualizations-in-r/)\).

If you want to get some inspiration on what visualization to create next, you can have a look at blogs dedicated to visualizations such as [FlowingData](https://flowingdata.com/).

## Data Science & Machine Learning with R

There are many beginner resources on how to do data science with R. A list of available online courses:

* [Andrew Conway’s Introduction to statistics with R](https://www.datacamp.com/introduction-to-statistics?tap_a=5644-dce66f&tap_s=10907-287229) \(subscription required\)
* [Data Analysis and Statistical Inference](https://www.coursera.org/course/statistics)
* [Data Analysis for life sciences](https://www.edx.org/course/data-analysis-life-sciences-1-statistics-harvardx-ph525-1x)
* [Data Science Specialization by Johns Hopkins](https://www.coursera.org/specializations/jhudatascience)

Alternatively, if you prefer a good read:

* [Practical Data Science With R](https://www.manning.com/books/practical-data-science-with-r)
* [R for Data Science](http://r4ds.had.co.nz/)
* [A Survival Guide to Data Science with R](http://togaware.com/onepager/)

Once your start doing some machine learning with R, you will quickly find yourself using packages such as [caret](https://cran.r-project.org/web/packages/caret), [rpart](https://cran.r-project.org/web/packages/rpart) and [randomForest](https://cran.r-project.org/web/packages/randomForest). Luckily, there are some great learning resources for these packages and Machine Learning in general. If you are just getting started,[this guide](https://machinelearningmastery.com/jump-start-machine-learning-in-r/) will get you going in no time. Alternatively, you can have a look at the books [Mastering Machine Learning with R](http://www.anrdoezrs.net/click-7948081-11260198-1448292209000?url=http%3A%2F%2Fshop.oreilly.com%2Fproduct%2F9781783984527.do%3Fcmp%3Daf-na-books-videos-product_cj_9781783984534_%2525zp&cjsku=9781783984527) and [Machine Learning with R.](http://www.kqzyfj.com/click-7948081-11260198-1448292209000?url=http%3A%2F%2Fshop.oreilly.com%2Fproduct%2F9781784393908.do%3Fcmp%3Daf-na-books-videos-product_cj_9781784394523_%2525zp&cjsku=9781784393908) If you are looking for some step-by-step tutorials that guide you through a real life example there is the [Kaggle Machine Learning course](https://www.datacamp.com/courses/kaggle-tutorial-on-machine-learing-the-sinking-of-the-titanic/?tap_a=5644-dce66f&tap_s=10907-287229) or you can have a look at [Wiekvoet’s blog](https://wiekvoet.blogspot.be/).

## Reporting Results in R

[R Markdown](https://rmarkdown.rstudio.com/) is an authoring format that enables easy creation of dynamic documents, presentations, and reports from R. It is a great tool for reporting your data analysis in a reproducible manner, thereby making the analysis more useful and understandable. R markdown is based on [knitr](https://cran.r-project.org/web/packages/knitr) and [pandoc](http://pandoc.org/). With R markdown, R generates a final document that replaces the R code with its results. This document can be in an html, word, pfd, ioslides, etc. format. You can even create interactive R markdown documents using Shiny. This 4 hour tutorial on [Reporting with R Markdown](https://www.datacamp.com/courses/reporting-with-r-markdown/?tap_a=5644-dce66f&tap_s=10907-287229) \(subscription required\) get’s you going with R markdown, and in addition you can use this [nice cheat sheet for future reference](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf).

Next to R markdown, you should also make sure to check out  [Shiny](https://shiny.rstudio.com/). Shiny makes it incredibly easy to build interactive web applications with R. It allows you to turn your analysis into interactive web applications without needing to know HTML, CSS or Javascript. RStudio maintains a [great learning portal](https://shiny.rstudio.com/tutorial/) to get you started with Shiny, including [this set of video tutorials](https://www.rstudio.com/resources/webinars/) \(click on the essentials of Shiny Learning Roadmap\). More [advanced topics](https://shiny.rstudio.com/articles/) are available, as well as a great set of [examples](https://shiny.rstudio.com/gallery/).

[![image00](https://i2.wp.com/www.r-bloggers.com/wp-content/uploads/2015/12/image00-300x158.png?resize=300%2C158&ssl=1)](https://i2.wp.com/www.r-bloggers.com/wp-content/uploads/2015/12/image00.png?ssl=1)

## Learning advanced R topics in \(paid\) online courses

### [DataCamp](https://www.datacamp.com/?tap_a=5644-dce66f&tap_s=10907-287229)

[DataCamp](https://www.datacamp.com/?tap_a=5644-dce66f&tap_s=10907-287229) also offers access to **all** of its advance R courses for $25/month, these include:

* [R for SAS, SPSS and STATA Users](https://www.datacamp.com/courses/r-for-sas-spss-and-stata-users-r-tutorial/?tap_a=5644-dce66f&tap_s=10907-287229)
* [A Hands-on Introduction to Statistics with R](https://www.datacamp.com/introduction-to-statistics/?tap_a=5644-dce66f&tap_s=10907-287229)
* [Intermediate R](https://www.datacamp.com/courses/intermediate-r/?tap_a=5644-dce66f&tap_s=10907-287229)
* [Importing Data Into R](https://www.datacamp.com/courses/importing-data-into-r/?tap_a=5644-dce66f&tap_s=10907-287229)
* [Data Manipulation in R with dplyr](https://www.datacamp.com/courses/dplyr-data-manipulation-r-tutorial/?tap_a=5644-dce66f&tap_s=10907-287229)
* [Data Analysis in R, the data.table Way](https://www.datacamp.com/courses/data-table-data-manipulation-r-tutorial/?tap_a=5644-dce66f&tap_s=10907-287229)
* [Data Visualization in R with ggvis](https://www.datacamp.com/courses/ggvis-data-visualization-r-tutorial/?tap_a=5644-dce66f&tap_s=10907-287229)
* [Data Visualization with ggplot2 \(1\)](https://www.datacamp.com/courses/data-visualization-with-ggplot2-1/?tap_a=5644-dce66f&tap_s=10907-287229)
* [Data Visualization with ggplot2 \(2\)](https://www.datacamp.com/courses/data-visualization-with-ggplot2-2/?tap_a=5644-dce66f&tap_s=10907-287229)
* [Introduction to Machine Learning](https://www.datacamp.com/courses/introduction-to-machine-learning-with-r/?tap_a=5644-dce66f&tap_s=10907-287229)
* [Reporting with R Markdown](https://www.datacamp.com/courses/reporting-with-r-markdown/?tap_a=5644-dce66f&tap_s=10907-287229)

### [Udemy](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=406329.3010&type=3&subid=0)

Another company is [Udemy](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=406329.4926&type=3&subid=0). While they do not offer video + interactive sessions like [DataCamp](https://www.datacamp.com/?tap_a=5644-dce66f&tap_s=10907-287229), they do offer extensive video lessons, covering some other topics in using R and learning statistics. For readers of R-bloggers, [Udemy is offering](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=406329.4926&type=3&subid=0) access to its courses for $15-$30 per course, use the code **RBLOGGERS30** for an extra 30% discount. Here are some of their courses:

**Advanced R courses:** 

* Regression modelling
  * [Comprehensive Linear Modeling with R](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6438&type=3&subid=0) \(15 Hours of video\)
  * [Linear regression in R for Data Scientists \(7 hours\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Flinear-regression-in-r-for-data-scientists)
  * [Linear Mixed-Effects Models with R](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6431&type=3&subid=0) \(11 Hours of video\)
  * [Linear Regression, GLMs and GAMs with R \(8 hours\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Flinear-regression-glms-and-gams-with-r)
  * [Forecasting Models with R \(5 hours\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Fforecasting-models-with-r)
  * [Time Series Analysis and Forecasting in R](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6440&type=3&subid=0) \(3 Hours of video\)
  * [Regression, Data Mining, Text Mining, Forecasting using R \(32 hours\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Fdata-science-using-r)
* Statistical/machine learning
  * [Bayesian Computational Analyses with R](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6439&type=3&subid=0) \(12 Hours of video\)
  * [Data Science and Machine Learning Bootcamp with R \(17 hours\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Fdata-science-and-machine-learning-bootcamp-with-r)
  * [Decision Tree – Theory, Application and Modeling using R \(5 hours\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Fdecision-tree-theory-application-and-modeling-using-r)
  * [Data Mining with R: Go from Beginner to Advanced! \(12 hours\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Fdata-mining-with-r-go-from-beginner-to-advanced)
  * [Machine Learning A-Z™: Hands-On Python & R In Data Science \(40 hours\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Fmachinelearning)
  * [Applied Multivariate Analysis with R](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6433&type=3&subid=0) \(13 Hours of video\)
*  Visualization
  * [Graphs in R \(ggplot2, plotrix, base R\) – Data Visualization with R Programming Language](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6430&type=3&subid=0) \(5 Hours of video\)
  * [Multivariate Data Visualization with R](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6432&type=3&subid=0) \(7 Hours of video\)
* Other topics
  * [Create Interactive Web Applications with the R Shiny Package \(8 hours\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Fr-shiny-apps)
  * [More Data Mining with R](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6434&type=3&subid=0) \(11 Hours of video\)
  * [Text Mining, Scraping and Sentiment Analysis with R](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6435&type=3&subid=0) \(4 Hours of video\)
  * [Text Analytics/Text Mining Using R \(1 hour\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Ftext-analyticstext-mining-using-r)
  * [Core Spatial Data Analysis: Introductory GIS with R and QGIS \(2 hours\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Fcore-spatial-data-analysis-with-r-and-qgis)
  * [Spatial Data Analysis with R, QGIS & More \(4 hours\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Fintermediate-spatial-data-analysis-with-r-qgis-more)
* R programming
  * [The Comprehensive Programming in R Course](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6429&type=3&subid=0) \(25 Hours of video\)
  * [R Programming for Simulation and Monte Carlo Methods](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6436&type=3&subid=0) \(12 Hours of video\)
  * [Programming Statistical Applications in R](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6437&type=3&subid=0) \(12 Hours of video\)
  * [R Programming A-Z™: R For Data Science With Real Exercises! \(10 hours\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Fr-programming)
  * [R Programming: Advanced Analytics In R For Data Science \(6 hours\)](https://click.linksynergy.com/deeplink?id=eO5bByfCCNo&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Fr-analytics)

**Introductory R courses:** 

* [Introduction to R](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6441&type=3&subid=0) \(15 Hours of video\)
* [Applied Data Science with R](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6442&type=3&subid=0) \(11 Hours of video\)
* [R Level 1 – Data Analytics with R](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6443&type=3&subid=0) \(6 Hours of video\)
* [Learn R Programming from Scratch](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6444&type=3&subid=0) \(2 Hours of video\)
* [Statistics in R – The R Language for Statistical Analysis](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6445&type=3&subid=0) \(3 Hours of video\)
* [Machine Learning and Statistical Modeling with R Examples](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6446&type=3&subid=0) \(3 Hours of video\)
* [Introduction To Data Science](https://click.linksynergy.com/fs-bin/click?id=eO5bByfCCNo&offerid=323058.6447&type=3&subid=0) \(6 Hours of video\)

### [Statistics.com](http://www.statistics.com/)

[Statistics.com](http://www.statistics.com/) is an online learning website with 100+ courses in statistics, analytics, data mining, text mining, forecasting, social network analysis, spatial analysis, etc.

They have kindly agreed to offer R-Bloggers readers a reduced rate of $399 for any of their 23 courses in R, Python, SQL or SAS.  These are high-impact courses, each 4-weeks long \(normally costing up to $589\).  They feature hands-on exercises and projects and the opportunity to receive  answers online from leading experts like Paul Murrell \(member of the R core development team\), Chris Brunsdon \(co-developer of the GISTools package\), Ben Baumer \(former statistician for the NY Mets baseball team\), and others. These instructors will answer all your questions \(via a private discussion forum\) over a 4-week period.

You may use the code “R-Blogger16″ when registering.  You can register for any R, Python, Hadoop, SQL or SAS course starting on any date. Here is a list of the [R related courses](https://bit.ly/1O3zgUA):

Using R as a statistical package

* [R for Statistical Analysis](http://www.statistics.com/R-for-statistical-analysis/?utm_source=r-bloggers&utm_medium=blog&utm_campaign=courses_in_R)
* [Modeling in R](http://www.statistics.com/modeling-in-R/?utm_source=r-bloggers&utm_medium=blog&utm_campaign=courses_in_R)
* [Visualization in R using ggplot2](https://bit.ly/17OHHC7%E2%80%8B)
* [Graphics in R](http://www.statistics.com/graphics-in-R/?utm_source=r-bloggers&utm_medium=blog&utm_campaign=courses_in_R)
* [Logistic Regression](http://www.statistics.com/course-catalog/logistic-regression/?utm_source=r-bloggers&utm_medium=blog&utm_campaign=courses_in_R)
* [Bayesian Statistics in R](https://bit.ly/1b2zSfl%E2%80%8B)

Building R programming skills – for those familiar with R, or experienced with other programming languages or statistical computing environments

* [R Programming – Intermediate](https://bit.ly/OsG4nn) One year of daily R use required before taking this course
* [R Programming – Advanced](https://bit.ly/189T4GN) Two years of daily R use required before taking this course

Applying R to specific domains or applications

* [Applied Predictive Analytics](https://bit.ly/18NA3Go%E2%80%8B)
* [SQL and R – Introduction to Database Queries](http://www.statistics.com/course-catalog/sql-and-r-database-queries/?utm_source=r-bloggers&utm_medium=blog&utm_campaign=courses_in_R)
* [Biostatistics in R with Clinical Trial Applications](http://www.statistics.com/biostatistics-R/?utm_source=r-bloggers&utm_medium=blog&utm_campaign=courses_in_R)
* [Data Mining in R](https://bit.ly/14JGiZz%E2%80%8B)
* [Mapping in R](https://bit.ly/1dZKL2E%E2%80%8B)
* [Spatial Analysis Using R](https://bit.ly/1aonWlf)

You may pick any of the R courses from their catalog page:  
 [www.statistics.com/course-catalog/](https://bit.ly/1XjFiaF)

## Next steps

Once you become more fluent in writing R syntax \(and consequently addicted to R\), you will want to unlock more of its power \(read: do some really nifty stuff\). In that case make sure to check out [RCPP](http://www.rcpp.org/), an R package that makes it easier for integrating C++ code with R, or [RevoScaleR](http://www.revolutionanalytics.com/whitepaper/revolution-r-enterprise-scaler-fast-highly-scalable-r-multiple-processors) \(start the [free tutorial](https://www.datacamp.com/courses/big-data-revolution-r-enterprise-tutorial/?tap_a=5644-dce66f&tap_s=10907-287229)\).

After spending some time writing R code \(and you became an R-addict\), you’ll reach a point that you want to start writing your own R package. Hilary Parker from Etsy has written a [short tutorial](http://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/) on how to create your first package, and if you’re really serious about it you need to read [R packages](http://r-pkgs.had.co.nz/), an upcoming book by Hadley Wickham that is already available for free on the web.

If you want to start learning on the inner workings of R and improve your understanding of it, the best way to get you started is by reading [Advanced R](http://adv-r.had.co.nz/).

Finally, come visit us again at [**R-bloggers.com**](https://www.r-bloggers.com/) to read of the latest news and tutorials from bloggers of the R community.

