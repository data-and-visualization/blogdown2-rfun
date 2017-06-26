# README

This is a test site to see if I can manage the RFUN website out of libjohn on behalf of github/askdata@d.e.

1. `library(blogdown)`

    - devtools::install_github('rstudio/blogdown')
    - blogdown::install_hugo()  # but if you have more than one site built on your local workstation, then skip this
    
2. `blogdown::new_site(theme = "jpescador/hugo-future-imperfect")`  # must be a completely *empty directory* except for .Rproj file

3. `serve_site()`