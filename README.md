# LESS Boilerplate

LESS Boilerplate - Simple LESS mixins library

# Folder structure

    less-boilerplate
      ├── mixins
      │  ├── utilities.less.....................utility functions such as clearfix()
      │  └── vendor-prefixes.less...............all about vendor prefix such as border-radius, transition
      ├── style.less............................main stylesheet
      ├── variables.less........................all variables
      ├── CHANGELOG.MD
      └── README.md

# Full Featured list

- [Material Design Color](http://www.google.com/design/spec/style/color.html)
- Compatibility with [Bootstrap 3](http://getbootstrap.com/)
- Code Standard : [LESS doc](http://lesscss.org/)

# Thanks

- [Preboot 2](http://getpreboot.com/) - MIT
- [Lesshat 3.0.2](https://github.com/madebysource/lesshat) - MIT

# MIXINS

## utilities.less

- BORDER
- GRADIENT
- CLEARFIX
- UTILITIES
  - text-hide (image replacement)
  - size
  - square
  - overflow-hidden
  - overflow-visible
  - size
  - circle
  - padding-none (padding 0)
  - margin-none (margin 0)
  - border-none
  - border-radius-none
  - transition-none (transition none)
  - print-none (display none on media print)
  - text-overflow
  - font-face (e.g. #font > .font-face)
  - content-columns
  - opacity
  - resizable

## vendor-prefixes.less

- BORDER-RADIUS
- ZOOM-IN
- ANIMATIONS
- BACKFACE-VISIBILITY
- BOX-SIZING
- BOX-SHADOW
- TEXT-SHADOW
- TEXT-SIZE-ADJUST
- PLACEHOLDER
- TRANSFORM
- TRANSITION
- USER-SELECT
- HYPHENS
- OPACITY
- FILTER
- BACKGROUND
- APPEARANCE
- TAB-SIZE
- WORD-BREAK
- POINTER-EVENTS

## style.less

- GENERAL
- HEADER
- CONTENT
- FOOTER
- VENDOR

## variable.less

- COLOR
  - gray (many levels of gray)
  - scheme (color scheme)
  - general (e.g. bg, text, link color)
- FONT
- BORDER
- SCREEN
- CUSTOM
