# Change Log
All notable changes to this project will be documented in this file.

## Scalingo buildpack

### 2022-09-13
- Changed stack check from Heroku-X to Scalingo-x.

## Heroku original buildpack

### 2022-05-19
- Added support for Heroku-22.

### 2022-03-30
- Fixed bug where arguments with spaces don't work.

### 2022-03-29
- Explicitly unset `LD_PRELOAD` env variable.

### 2022-01-04
- Removed support for Cedar-14 and Heroku-16.
