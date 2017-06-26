# README

This is a test site to practice managing the RFUN website out of libjohn on behalf of github/askdata@d.e.

1. `library(blogdown)`

    - devtools::install_github('rstudio/blogdown')
    - blogdown::install_hugo()  # but if you have more than one site built on your local workstation, then skip this
    
2. `blogdown::new_site(theme = "jpescador/hugo-future-imperfect")`  # must be a completely *empty directory* except for .Rproj file

3. `serve_site()`

## Notes

There were some problems with Hugo Building from Rmarkdown.  

- Posted to stackExchange

> sounds like a bug that has been fixed in Hugo 0.24.1 the other day. Please restart your R session, try to reinstall blogdown, and update Hugo:

- `devtools::install_github('rstudio/blogdown')`
- `blogdown::update_hugo()`