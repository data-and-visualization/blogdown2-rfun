# README

# README

<!-- badges: start -->
<!-- badges: end -->

The process of upgrading versions of blogdown and blogdown's Hugo instance is fraught.  Here are some investigations and tips.

This RStudio project uses the [dopetrope](https://github.com/curtiscde/hugo-theme-dopetrope) theme with the latest CRAN version of blogdown (ver 1.9) ; `blogdown::hugo_version()` = 0.96.0 

## How to start the Hugo-blogdown server on local

1. RStudio IDE > Addins > Serve site (have blogdown package installed)

## How to create a new blog post

1. RStudio IDE > Addins > New post (have blogdown package installed)
2. Make modifications based on earlier .md files found in `content/blog`

## How to create a new portfolio stub

Make a copy of earlier content in `content/portfolio`; modify.

## Hugo specific 
notes can be found in [another README](README_hugo_not_blogdown_commands.md).  For this sub-trial, I installed a separate (non-blogdwon) Hugo instance on my system so that I could investigate aspects of how the dopetrope theme has changed.

## Dopetrope theme

- This theme is not a perfect fit with blogdown.  It seems to use some rather idiosyncratic markdown.  In this way the Hugo command `hugo new posts/hello-world.md` (or the Blogdown:  `RStudio > Addins > New post`) doesn't follow the same markdown format as more standard Hugo Theme seem to prefer.  But it seems to work file (in both Hugo "pure" and blogdown-hugo).  Anyway, it is easy enough to modify based on the format of existing documents found within `content/portfolio` or `content/blog`

## Blogdown approach

- To install this theme I used File > New Project > New Directory > Website using blogdown
- To identify the theme I plugged in the github usernamne/reponame naming convention via the wizard
- I then updated files based on customized content from the [rfun github repo](https://github.com/data-and-visualization/blogdown2-rfun/). Those file changes are documented in the version control history (i.e. early git commits) for this project.  Those commit messages reference copying files from _mope_.  Mope was an earlier attempt that basically consists the updated dopetrope themes plus the custom files found at the [blogdown-rfun site](https://github.com/data-and-visualization/blogdown2-rfun).

### Pin a hugo version to a particular RStudio project

- https://www.rstudio.com/blog/blogdown-v1.0/#hugo-versioning-system

### Checking Hugo

There are many ways the Hugo and Blogdown could talk over each other.  Here are a collection of check functions

- https://www.rstudio.com/blog/blogdown-v1.0/#checking-functions


## Netlify / Deploy

more notes should go here

***

## OLD README stuff

This reposistory contains the raw files for the [Rfun](https://github.com/data-and-visualization/Rfun) website.   The website is constructed using the [rstudio/blogdown](https://github.com/rstudio/blogdown) package.   

## Create Site -- Notes
1. `library(blogdown)`

    - devtools::install_github('rstudio/blogdown')
    - blogdown::install_hugo()  # but if you have more than one site built on your local workstation, then skip this
    
2. `blogdown::new_site(theme = "curttimson/hugo-theme-dopetrope")`  # must be a completely *empty directory* except for .Rproj file

3. `serve_site()`  or `build_site()`

## Notes

There were some problems with Hugo Building from Rmarkdown.  

- Posted to stackExchange

> sounds like a bug that has been fixed in Hugo 0.24.1 the other day. Please restart your R session, try to reinstall blogdown, and update Hugo:

- `devtools::install_github('rstudio/blogdown')`
- `blogdown::update_hugo()`

## Site is served via Netlify.com

