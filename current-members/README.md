# for current lab members

## feeding schedule, fall 2016

Please let Luke know if you are sick or traveling on a day you're supposed to be feeding.

The guide for feeding the fish is [here](https://github.com/lukereding/cummings_lab_members/blob/master/current-members/feeding_guide.md).

| day | feeder |
| ---- | ---- |
| Sunday | Matt |
| Monday | Lily |
| Tuesday | Kelly |
| Wednesday | Caleb |
| Thursday | Matt |
| Friday | Randa |
| Saturday | TBD |


## water change schedule, fall 2016

All racks are labeled in yellow. Please refer to [how_to_do_water_changes.md](https://github.com/lukereding/cummings_lab_members/blob/master/current-members/how_to_do_water_changes.md) and [making_water.md](https://github.com/lukereding/cummings_lab_members/blob/master/current-members/making_water.md) for questions about water changes and making new water.

be sure to scroll the table to the right! there are 11 racks total!

'status' refers to whether there are fish on those racks or not. If there aren't fish tanks on a given rack, you don't need to water change!

| date | rack 1 | rack 2 | rack 3 | rack 4 | rack 5 | rack 6 | rack 7 | rack 8 | rack 9 | rack 10 | rack 11 |
| :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
| status | :tropical_fish: | :tropical_fish: | :tropical_fish: | :no_entry_sign: | :tropical_fish: | :tropical_fish: | :tropical_fish: | :tropical_fish: | :tropical_fish: | :no_entry_sign: | :no_entry_sign: |
| location | PAT 512 | PAT 512 | PAT 512 | PAT 512 | PAT 512 | PAT 512 | PAT 434B | PAT 434B | PAT 434B | PAT 434B | PAT 434B |
| **4 December**  | Rachel E. | Sarah | Luke | :no_entry_sign: | Ben | Sammy | Randa | Sam | Ben | :no_entry_sign: | :no_entry_sign: |
| **20 November**  | Rachel E. | Sarah | Ben | :no_entry_sign: | Luke | Sammy | Sam | Randa | Ben | :no_entry_sign: | :no_entry_sign: |
| **6 November**  | Rachel E. | Ben | Sarah | :no_entry_sign: | Randa | Sam | Sammy | Luke | Ben | :no_entry_sign: | :no_entry_sign: |
| **23 October**  | Rachel E. | Ben | Sarah | :no_entry_sign: | Randa | Sam | Lily | Sammy | Rachel E. | :no_entry_sign: | :no_entry_sign: |
| **10 October**  | :no_entry_sign: | Ben | Sammy | :no_entry_sign: | Sam | Randa | Lily | Sarah | :no_entry_sign: | :no_entry_sign: | :no_entry_sign: |
| **26 September**  | :no_entry_sign: | Sammy | Ben | :no_entry_sign: | Randa | Sam | Sarah | Lily  | :no_entry_sign: | :no_entry_sign: | :no_entry_sign: |
| **12 September**  | :no_entry_sign: | Sarah | Kelly | :no_entry_sign: | Lily | Luke | Sammy | Randa | :no_entry_sign: | :no_entry_sign: | :no_entry_sign: |
| **29 August**  | :no_entry_sign: | Kelly | Sarah | :no_entry_sign: | Luke :man: | Lily | Randa | Sammy | :no_entry_sign: | :no_entry_sign: | :no_entry_sign: |





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

