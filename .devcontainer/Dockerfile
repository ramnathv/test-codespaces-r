ARG VARIANT="4"
FROM ghcr.io/rocker-org/devcontainer/tidyverse:${VARIANT}


# Copy RStudio Preferences and RSession Configuration
COPY .rstudio/rstudio-prefs.json /etc/rstudio/rstudio-prefs.json
COPY .rstudio/rsession.conf /etc/rstudio/rsession.conf
