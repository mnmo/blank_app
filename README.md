blank_app
=========

Scaffold webapp and build system that we will use as basis for the
development of HTML5-based mobile apps.

[![Build Status](https://travis-ci.org/mnmo/blank_app.png?branch=master)](https://travis-ci.org/mnmo/blank_app)

Under Construction
------------------

This project is not ready for public consumption, it is under heavy
development and changing / breaking constantly. I use it for my personal
usecases and it is not intended to become a general purpose tool at the moment.

Look elsewhere for better boilerplates and frameworks.


Features / Goals
----------------

This app is basically a big [Gruntfile](http://gruntjs.com/) and a folder
hierarchy based on my personal preferences and tools, it aims for this
3 goals:

### 1. Work Offline
  - appcache manifest file auto updated for me
  - HTML5 Boilerplate best practices recommendations for
  Apache Server Configuration with patches to make the `appcache validate`
  command of Firefox Nightly's developer toolbar happy

### 2. Be Cross Platform
  - CSS autoprefixing
  - Polyfills (TBD)
  - Open Web Apps (Firefox OS) manifest
  - Ubuntu Touch HTML5 app packaging (work in progress)
  - Google Chrome installable app manifest (TBD)

### 3. Have Modular / Organized Source Code
  - HTML generation based on Handlebars layouts and partials
  - Stylesheets generated from SASS partials
  - Code separated into modules
  - Code linting
