# Purple Style Library
Global style library for Purple. Please see the Design system figma on how these styles are implemented

## Overview

Prefer CSS3 variables instead of sass variables

## Installing
`npm install `

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
`npm run build # build styles`

## Contributing
Do not add styles that are specific to a project