# Docker images for moonmoon [![Docker Build Status](https://img.shields.io/docker/build/moonmoonapp/moonmoon.svg?style=flat-square)](https://hub.docker.com/r/moonmoonapp/moonmoon/) [![Docker Pulls](https://img.shields.io/docker/pulls/moonmoonapp/moonmoon.svg?style=flat-square)](https://hub.docker.com/r/moonmoonapp/moonmoon/)

This repository takes advantage from Docker Hub's Automated Builds to generate
up-to-date images of moonmoon in various environments. At the time, these 
images are mostly intended for manual testing, but PR are welcome to make it
more production-ready.

The following tags are available:
- `nightly-php-7.2`
- `nightly-php-7.0` 
- `nightly-php-5.6`

A _webhook_ has been added to [moonmoon/moonmoon](https://github.com/moonmoon/moonmoon)
so any push will automatically re-build Docker images.
