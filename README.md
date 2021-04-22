
# Introuction to R for Geocomputing

Regardless of which programming language is your favourite, the R language for statistical computing is here to stay. This workshop introduces geoscientists to R using two flagship packages of the *tidyverse*: *ggplot2* (create elegant data visualizations using the grammar of graphics) and *dplyr* (a grammar of data manipulation). We'll use data familiar to geoscientists and approach the material from the point of view of those familiar with Python (but coders of all experience levels are encouraged to attend!).

Today you will learn the basics of R for geoscience using [ggplot2](https://ggplot2.tidyverse.org/), a popular visualization package for R. To get started:

1. Launch an RStudio IDE pre-loaded with today's exercises and solutions by clicking [here](https://rstudio.cloud/project/2472192) and logging in. You may need to create an account - this is easy to do and RStudio really won't send you any email!
2. Once the project is loaded you will see a flashing "temporary copy" at the top of the page. Click on "Save a Copy" to make sure your edits are saved if you close your window or loose your internet connection.

If you prefer, you can also run this tutorial locally. The steps for this are:

1. Install R if you haven't already ([Windows](https://cloud.r-project.org/bin/windows/), [MacOS](https://cloud.r-project.org/bin/macosx/), [Linux](https://cloud.r-project.org/bin/linux/))
2. Install [RStudio](https://www.rstudio.com/products/rstudio/download/#download)
3. Download the material by clicking the green __Clone or download__ button above. (Then click __Download Zip__ in the tab that appears). Unzip the file anywhere on your computer and double-click on the "r4transform2021.Rproj" button to launch RStudio. You will have to run all of the lines in INSTALL.R to make sure all the package you need are installed.

Resources for future learning:

- [R for Data Science](http://r4ds.had.co.nz) by Hadley Wickham and Garrett Grolemund
- [RStudio Cloud Primers](https://rstudio.cloud/learn/primers)
- [Master the Tidyverse](https://github.com/rstudio-education/master-the-tidyverse)

Many slides in this workshop are derivative work of [Master the Tidyverse](https://github.com/rstudio-education/master-the-tidyverse) by Garrett Grolemund of [RStudio](https://rstudio.com), and are licensed under a Creative Commons-BY license. The `warwick` dataset is a modified version of the [Warwick Mountain Lithgeochemistry](https://novascotia.ca/natr/meb/download/dp505dds.asp) dataset from the Nova Scotia Department of Energy and Mines, and is distributed as package data from the [geoscidata](https://github.com/paleolimbot/geoscidata) package.
