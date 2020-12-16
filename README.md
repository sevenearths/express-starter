I created this repo as a starting point for NodeJS projects going forward. Mainly because I don't want to install npm locally and want to containerise everything.

## Install

```
# make install
```

### Installing new packages

```
# vim docker-compose.builder.yml
...
  command: sh -c "npm install ... && npm update --save"
...
# make save-package
```

## Create a Project

```
# make create-project
```

## Run a local server

> This will only work after you have created a project with the abover command

```
# make dev
```
