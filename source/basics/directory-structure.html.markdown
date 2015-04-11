---
title: Directory Structure
---

# Directory Structure

The default Front-end installation consists of a directory structure which looks like this:

``` ruby
front-end/
	+-- app
	¦   +-- fonts
	¦   +-- images
	¦   +-- layouts
	¦   +-- scripts
	¦   +-- snippets
	¦   +-- styles
	¦   +-- vendor
	+-- build
	+-- node_modules
	+-- resources
	¦   +-- graphics
	¦   +-- layouts
	+-- .gitignore
	+-- .editorconfig
	+-- .gitattributes
	+-- .gitignore
	+-- .jshintrc
	+-- .yo-rc.json
	+-- Gruntfile.js
	+-- README.md
	+-- bower.json
	+-- config.json
	+-- divshot-dev.json
	+-- divshot-prod.json
	+-- divshot-staging.json
	+-- gulpfile.js
	+-- lint.yml
	+-- package.json
```

## Main Directories

Middleman makes use of the `app`, `build`, 

### App Directory

The `app` directory contains your main website source files to be built,
including your templates javascript, CSS and images.

### Build Directory

The `build` directory is where your static website files will be compiled and
exported to. There are 2 types of builds: `development` (unpacked files) and `production` (packed files).  



