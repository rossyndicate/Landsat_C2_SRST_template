# Landsat Collection 2 Surface Reflectance and Temperature Acquisition hub

Workflow to acquire Landsat Collection 2 Surface Reflectance and Surface Temperature products for lakes and reservoirs from point locations or lake polygons.

Note, before any code that requires access to GEE is run, you must execute the following command in your **zsh** terminal and follow the prompts in your browser.

`earthengine authenticate`

When complete, your terminal will read:

`Successfully saved authorization token.`

This token is valid for 7 days from the time of authentication.

## Repository Overview

This repository is powered by {targets}, an r-based workflow manager. In order to use this workflow, you must have a [Google Earth Engine account](https://earthengine.google.com/signup/), and you will need to [download, install, and initialize gcloud](https://cloud.google.com/sdk/docs/install). For common issues with `gcloud`, please [see the notes here](https://github.com/rossyndicate/ROSS_RS_mini_tools/blob/main/helps/CommonIssues.md).

## Completing the config.yml file

### Local Settings

location file: must contain lat, lon, uniqueid

### Google Settings

### Temporal Settings

### Spatial Settings

### Google Earth Engine Settings
