# HamRadioNewbie.com

## Overview

This repo contains the source for https://HamRadioNewbie.com, built via [Hugo](https://gohugo.io/).

## Usage

### Pre-reqs

```
# get a copy of the code
git clone https://github.com/loganmarchione/HamRadioNewbie.com.git
cd HamRadioNewbie.com
```

### Build instructions

#### Docker

```
# build the Dockerfile
docker compose -f docker-compose-dev.yml up -d

# view logs
docker compose -f docker-compose-dev.yml logs -f

# destroy when done
docker compose -f docker-compose-dev.yml down
```

### add, commit, push to kick off GitHub Actions

```
git add .
git commit -m "Update some stuff"
git push
```