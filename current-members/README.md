# for current lab members

## feeding schedule, summer 2017

Please let Luke know if you are sick or traveling on a day you're supposed to be feeding.

The guide for feeding the fish is [here](https://github.com/lukereding/cummings_lab_members/blob/master/current-members/feeding_guide.md).

| day  |  feeder |
|---|---|
| Monday  | Rachel  |
| Tuesday | Rachel  |
| Wednesday  | Rachel  |
| Thursday  | Rachel  |
| Friday  | Rachel|
| Saturday | TBD  |
| Sunday | TBD  |

## student schedules, summer 2017

You can find the schedules of lab folks here in summer 2017 [here](https://docs.google.com/a/utexas.edu/spreadsheets/d/1_RQHVHNj1qwYX0NWWUdbTGjW-MdV_dJ0u7bmDLMwjGE/edit?usp=sharing) (must be logged into your UT Google account to view or edit).

## water change schedule, summer 2017

The water change schedule for summer 2017 can be found [here](https://docs.google.com/spreadsheets/d/11rDYFusCRDkfhVnJj6glyc-7UZe_sjGYtff7ETf30nk/edit#gid=0).

## BFL Daily Inspections

The schedule for BFL visits can be found [here](https://docs.google.com/spreadsheets/d/1P8ZHOhtR9YWiSQtk04iip2XgDmuTlmmn8ljlmesAvPg/edit#gid=0).

When you go out to BFL to inspect the tanks, please remember: 

(1) To follow the guidelines [here](https://github.com/lukereding/cummings_lab_members/blob/master/current-members/bfl_daily_checklist.md). 

(2) Fill out the [Google form](https://goo.gl/forms/ZdS6uDZQtyupwpEv2) upon returning.


## other points of interest

### cummings lab specific
- Materials related to the common garden experiment can be found [here](https://drive.google.com/drive/folders/0By-mmmYFVU9PdXdnMXp4RWxTdUU).
- The code associated with the program that undergrads use to score the common garden videos is [here](https://github.com/lukereding/common_garden).
- Kelly's numerosity analysis code can be found [here](https://github.com/kjw2539/numerosityanalysis).

### GUI software
- [Midador](https://fathom.info/mirador/) - for exploring complex datasets with many variables, seeing what variables are most highly correlated with some other variable of interest. Useful in the early stages of analyzing a large, complex dataset
- [Gephi](https://gephi.org/) - illustrater for networks/graphs

### R
- [R for data science](http://r4ds.had.co.nz/): your guide for wrangling, plotting, and summarizing data in R   
- Luke's introduction to R and data analysis aimed for undergrads can be found [here](http://rpubs.com/lukereding/162259)
- Trying to learn an R package? Luke has some examples and tutorials [here](https://github.com/lukereding/random_scripts/blob/master/r_tutorials.R)  

**R packages and resources of interest:**
#### data visualization
- [pheatmap](https://github.com/raivokolde/pheatmap) - for creating attractive heatmaps
- [corrrplot](https://cran.r-project.org/web/packages/corrplot/vignettes/corrplot-intro.html) - for creating nice plots of correlations between variables
- [viridis](https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html) - a nice perceptually uniform, colorblind-friendly colormap
- [ggplot2 cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf)
- [directlabels](http://directlabels.r-forge.r-project.org/) - for those that harbor an antipathy for unweidy legends. Automatically places labels for (1) line plots or (2) scatterplots with >2 groups.
- [ggrepel](https://github.com/slowkow/ggrepel/blob/master/vignettes/ggrepel.md) - following a similar philosophical approach as `directlabels`, the purpose of `ggrepel` is to label the individual data points on a scatterplot with meaningly labels.
- [ggalt](https://github.com/hrbrmstr/ggalt) - contains additional `geoms` for use in `ggplot2`. Most useful: `geom_lollipop` and `geom_dumbbell`
- [ggthemes](https://github.com/jrnold/ggthemes) - additional useful color schemes and looks for graphs in `ggplot2`
- [ggforce](https://cran.r-project.org/web/packages/ggforce/vignettes/Visual_Guide.html) - additional functions for using with `ggplot2`. Notably, `geom_sina()` allows the creation of sinaplots (like in Brady et al. 2015 Science) and `facet_zoom()` allows you to show a zoomed-in part of a graph. 
- [ggally](http://ggobi.github.io/ggally/) - a collection of functions that extend `ggplot2`. Includes `ggparcoord` for plotting parallel coordinates and `ggpairs` to create nice summaries of dataframes with (equivalent of `plot(dataframe)` in base R).

#### quality control
- [visdat](https://github.com/njtierney/visdat) - for visualizing missing data in a dataframe. Run this once you have a dataframe and but _before_ you do any analysis on it.
- [ggmissing](https://github.com/njtierney/ggmissing) - for visualizing missing data in `ggplot2`. Useful as an alternative / second step after running `vis_dat`. 
- [wakefield](https://github.com/trinker/wakefield#demonstration) - for generating random datasets for function testing, etc.

#### data wrangling
- [dplyr & tidyr](https://rpubs.com/bradleyboehmke/data_wrangling) - for working with dataframes and making your data tidy
- [purrr](https://github.com/hadley/purrr) - for functional programming. The `map` functions this packages provides are really powerful when paired with the `mutate` class of functions in dplyr
- [data wrangling cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)

#### modeling
- [broom](https://github.com/dgrtwo/broom) - converts model outputs to dataframes for easier manipulation and plotting with ggplot
- [modelr](https://github.com/hadley/modelr) - useful modeling functions

#### version control / repeatability
- [packrat](http://rstudio.github.io/packrat/commands.html) - for keeping track of installed packages, and versions of those packages, for a given project
- [R markdown cheatsheet](https://www.rstudio.com/wp-content/uploads/2016/03/rmarkdown-cheatsheet-2.0.pdf)

