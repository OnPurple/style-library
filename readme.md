# Purple Style Library
Global style library for Purple. Please see the Design system figma on how these styles are implemented

## Overview

Prefer CSS3 variables instead of sass variables.

The dist contains the global CSS files. Mixins are not included in the build and
must be imported to your sass files.

## Installing
`npm i git@github.com:OnPurple/style-library.git`
## Getting the global styles
`@import 'node_modules/_/dist/global.min.css'`

## Using mixins in your SCSS files
`@import 'node_modules/_/sass/base/base'`

## Project Structure
### Base
SASS variables for configuring mixins

### Components
SASS files containing utitliy classes for creating components
  - Buttons
  - Links

### Mixins
Contains common mixins

### Utilities
Helper mixins. These mixins can be used, but are also used in the mixins defined in the mixins directory

### Variables
Defines the global CSS variables
  - Animations
  - Typography
  - Spacing
  - Colors


## Local Development
`npm run lint  # lint SCSS`

The GH actions workflow will build and push to the release branch

## Contributing
Do not add styles that are specific to a project