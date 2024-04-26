---
title: Home
layout: home
nav_order: 1
---
# NMFS Open Science Docker Stack

## THE DOCKER STACK IS IN ACTIVE DESIGN and DEVELOPMENT 

### Beta release targeted for June 1, 2024.

These are a collection of container images to provide standardized environments for Python and R computing build off the [Rocker](https://rocker-project.org/images/devcontainer/images.html), [Pangeo](https://github.com/pangeo-data/pangeo-docker-images) and Jupyter base images. This repo holds the (mostly) stable docker stack for specific pipelines used in Fisheries. Our development and testing sandbox is here: [nmfs-opensci/container-images](https://github.com/nmfs-opensci/container-images) which is our sandbox and development location. Why use a container? Watch this video from Yuvi Panda (Jupyter Project) [video](https://www.youtube.com/watch?v=qgLPpULvBbQ) and read about the Rocker Project in the R Project Journal [article](https://journal.r-project.org/archive/2017/RJ-2017-065/RJ-2017-065.pdf) by Carl Boettiger and Dirk Eddelbuettel.

## Stable set of images

There are many other images in the `images` folder that are experimental in nature.
  

| Image           | Description                            | Size | Link | Dockerfile |
|-----------------|----------------------------------------|------|------|------------|
| nmfs-opensci-python-base   | Geospatial Python based on NASA Openscapes image  | ![](https://ghcr-badge.egpl.dev/nmfs-opensci/container-images%2Fnmfs-opensci-python-base/size?color=%2344cc11&tag=latest&label=image+size&trim=) | [nmfs-opensci-python-base](https://github.com/nmfs-opensci/container-images/pkgs/container/container-images%2Fnmfs-opensci-python-base) | [Dockerfile](https://github.com/nmfs-opensci/container-images/tree/main/images/nmfs-opensci-python-base)
| py-rocket-base   | Tidyverse based R image with Python  | ![](https://ghcr-badge.egpl.dev/nmfs-opensci/container-images%2Fpy-rocket-base/size?color=%2344cc11&tag=latest&label=image+size&trim=) | [py-rocket-base](https://github.com/nmfs-opensci/container-images/pkgs/container/container-images%2Fpy-rocket-base) | [Dockerfile](https://github.com/nmfs-opensci/container-images/tree/main/images/py-rocket-base)
| py-rocket-geospatial   | Geospatial R and Python image | ![](https://ghcr-badge.egpl.dev/nmfs-opensci/container-images%2Fpy-rocket-geospatial/size?color=%2344cc11&tag=4.3.3-3.10&label=image+size&trim=) | [py-rocket-geospatial](https://github.com/nmfs-opensci/container-images/pkgs/container/container-images%2Fpy-rocket-geospatial) | [Dockerfile](https://github.com/nmfs-opensci/container-images/tree/main/images/py-rocket-geospatial)
| arcgis          | For using ArcGIS within Jupyter Lab      | ![](https://ghcr-badge.egpl.dev/nmfs-opensci/container-images%2Farcgis/size?color=%2344cc11&tag=latest&label=image+size&trim=) | [arcgis](https://github.com/nmfs-opensci/container-images/pkgs/container/container-images%2Farcgis) | [Dockerfile](https://github.com/nmfs-opensci/container-images/tree/main/images/arcgis)
| coastwatch       | CoastWatch Python + R      | ![](https://ghcr-badge.egpl.dev/nmfs-opensci/container-images%2Fcoastwatch/size?color=%2344cc11&tag=latest&label=image+size&trim=) | [coastwatch](https://github.com/nmfs-opensci/container-images/pkgs/container/container-images%2Fcoastwatch) | [Dockerfile](https://github.com/nmfs-opensci/container-images/tree/main/images/coastwatch)
| cmip6-cookbook           | Tooling for working with CMIP6 climate simulations      | ![](https://ghcr-badge.egpl.dev/nmfs-opensci/container-images%2Fcmip6-cookbook/size?color=%2344cc11&tag=latest&label=image+size&trim=) | [cmip6-cookbook](https://github.com/nmfs-opensci/container-images/pkgs/container/container-images%2Fcmip6-cookbook) | [Dockerfile](https://github.com/nmfs-opensci/container-images/tree/main/images/cmip6-cookbook)
| echopype         | Tooling for ocean sonar (acoustics) data processing  | ![](https://ghcr-badge.egpl.dev/nmfs-opensci/container-images%2Fechopype/size?color=%2344cc11&tag=latest&label=image+size&trim=) | [echopype](https://github.com/nmfs-opensci/container-images/pkgs/container/container-images%2Fechopype) | [Dockerfile](https://github.com/nmfs-opensci/container-images/tree/main/images/echopype)
| VAST             | VAST with R 4.3.3  | ![](https://ghcr-badge.egpl.dev/nmfs-opensci/container-images%2Fvast/size?color=%2344cc11&tag=latest&label=image+size&trim=) | [vast](https://github.com/nmfs-opensci/container-images/pkgs/container/container-images%2Fvast) | [Dockerfile](https://github.com/nmfs-opensci/container-images/tree/main/images/vast)
| aomlomics-jh     | NOAA AOML omics image for amplicon sequence processing workflow (adapted for JupyterHub deployment)  | ![](https://ghcr-badge.egpl.dev/nmfs-opensci/container-images%2Faomlomics-jh/size?color=%2344cc11&tag=latest&label=image+size&trim=) | [aomlomics-jh](https://github.com/nmfs-opensci/container-images/pkgs/container/container-images%2Faomlomics-jh) | [Dockerfile](https://github.com/nmfs-opensci/container-images/tree/main/images/aomlomics-jh)


*Click on the image name in the table above for a current list of installed packages and versions*
