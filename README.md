# Create a report of download statistics from PyPI, CRAN, and GitHub using RMarkdown

## About

This repo contains the RMarkdown code that reports on: 

- Download statistics from PyPI
- Download statistics from CRAN
- Clone statistics from GitHub

As is, the RMarkdown file generates a static HTML report. 

## Pre-requisites

This assumes that you have a repo with the same name hosted across PyPI and CRAN, e.g. 'igraph', 'vivainsights'. 

Please change the parameters in the RMarkdown document accordingly in order to pull the correct statistics. 

## Customizing the report content

This RMarkdown can be customized to only show statistics from one or more of the above components. Simply edit the RMarkdown file to tailor content. 

## Downloading and merging with previous records

Due to data retention issues, this script also downloads the statistics from PyPI and CRAN, and merges with the de-duplicated last downloaded records. When run as a regular job, this will ensure that long-running download statistics can be preserved and reported on beyond the 14 day limit. 

## Contributing

Please use GitHub Issues for bugs and feature requests. If you have a template that you would like to contribute, please feel free to fork and create a pull request. Thanks!
