# log of command to work on this project

```r
rmarkdown:::site_skeleton(getwd())
# append string to the end of _site.yml
cat("output_dir: docs", file = "_site.yml", sep = "\n", append = TRUE)
# add an empty file to the project
file.create(".nojekyll")
```

