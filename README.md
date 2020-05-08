## Build Rmd Site from Vignettes

> Github action to build a Rmd site from an R package vignettes folder

It should have a valid `_site.yml` and `index.Rmd` file under `vignettes/` folder.

If the package has a `_README.md` file in that same folder then it will render a github document and place it on the root folder *(along with READM_files folder)*

### Dockerfiles

It has 2 dockerfiles:

* Dockerfile - used for github action and doesn't need any long actions to build
* Dockerfile.build - Base image that gets build every few days with latest upstream


