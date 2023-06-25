FROM nginx:latest

### Common
# Sys packages
RUN apt-get -y update
RUN apt-get -y install git

# Add user for laravel application
RUN groupadd -g 1000 ad
RUN useradd -u 1000 -ms /bin/bash -g ad ad

# Work in the specific space
WORKDIR /app
#USER ad




