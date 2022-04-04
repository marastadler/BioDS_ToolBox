01a-preprocess-metadata
================
Compiled at 2022-04-04 13:38:32 UTC

``` r
here::i_am(paste0(params$name, ".Rmd"), uuid = "e550e5c0-dc25-48b4-a5b5-d7282a8b65ae")
```

The purpose of this document is …

``` r
library("conflicted")
```

``` r
# create or *empty* the target directory, used to write this file's data: 
projthis::proj_create_dir_target(params$name, clean = TRUE)

# function to get path to target directory: path_target("sample.csv")
path_target <- projthis::proj_path_target(params$name)

# function to get path to previous data: path_source("00-import", "sample.csv")
path_source <- projthis::proj_path_source(params$name)
```

## Tasks

The first task is …

## Files written

These files have been written to the target directory,
`data/01a-preprocess-metadata`:

``` r
projthis::proj_dir_info(path_target())
```

    ## # A tibble: 0 × 4
    ## # … with 4 variables: path <fs::path>, type <fct>, size <fs::bytes>,
    ## #   modification_time <dttm>
