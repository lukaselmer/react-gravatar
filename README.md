react-gravatar
==============

React component for rendering a gravatar profile image

## Demo
http://kyleamathews.github.io/react-gravatar/examples/

## Install
`npm install react-gravatar`

## Usage
See https://en.gravatar.com/site/implement/images/ for documentation on
all the options.

### Defaults
* 50x50 image
* g rated photos
* http
* retro backup faces for emails without profiles

### Example that uses defaults
`<Gravatar email="mathews.kyle@gmail.com" />`

## Example that overrides all defaults
`<Gravatar email="mathews.kyle@gmail.com" size=100 rating="pg" https
default="monsterid" />`
