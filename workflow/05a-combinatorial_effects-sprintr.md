05a-combinatorial\_effects-sprintr
================
Compiled at 2022-04-04 13:38:44 UTC

``` r
here::i_am(paste0(params$name, ".Rmd"), uuid = "5775b14e-be11-4bea-985e-816548afa7f9")
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
`data/05a-combinatorial_effects-sprintr`:

``` r
projthis::proj_dir_info(path_target())
```

    ## # A tibble: 0 × 4
    ## # … with 4 variables: path <fs::path>, type <fct>, size <fs::bytes>,
    ## #   modification_time <dttm>
