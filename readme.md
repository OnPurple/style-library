# Purple Style Library
Global style library for Purple. Please see the Design system figma on how these styles are implemented

## Overview

- Prefer CSS3 variables instead of sass variables
- Drupal should host the main global.css file for the purple.com domain

## Installing
`npm i git+ssh://git@github.com/OnPurple/style-library.git#release`

## Updating
`npm update @purple/style-libray`

## How to get the global styles
`@import 'node_modules/@purple/style-library/dist/global'`

## Using mixins in your SCSS files
Please make sure the global styles are on the page before using the mixins. Otheriwse
they will be styled incorrectly. This is an optional import.

`@import 'node_modules/@purple/style-library/sass/base/_base'`

You can also import specific files in the sass directory for a more granular approach.

## Font Families and icons
Fonts and Icons are hosted on Drupal.

## Project Structure
### Base
SASS variables for configuring mixins. This direcoty shouldn't change that much

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