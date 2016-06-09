# Material Typography

Typography based on Google's Material Design Standard; available in CSS, LESS, SASS, SCSS, and Stylus.

[![Build Status](https://travis-ci.org/juliancoleman/material-typography.svg?branch=master)](https://travis-ci.org/juliancoleman/material-typography)

### Install Instructions

#### NPM

```
npm install --save material-typography
```

#### Bower

```
bower install material-typography
```

Or simply download the `.zip` and place it in your project folder wherever you'd like, then include your flavor of `typography` in your primary stylesheet.

For example:

```css
@import "material-typography/css/typography.min.css";
```

Or

```html
<link rel="stylesheet" href="node_modules/material-typography/css/typography.min.css" />
```

### Usage instructions

If you don't want the typography to be so intrusive, simply find the specific `typography` file for your desired preprocessor, and comment out the `enforce-typography` import. This will be moved to a variable in a future release.

All elements may be styled very specifically with the use of several classes. These classes are as follows: (please use them semantically)

```
//  ordered by semantic priority
.md-display-4
.md-display-3
.md-display-2
.md-display-1
.md-headline
.md-title
.md-subhead
.md-body-1
.md-body-2
.md-caption
.md-button
```

These are the equivalents of using the following plain HTML tags if `enforce-typography` is enabled:

```
h1
h2
h3
h4
h5
h6
h7 // a custom tag name
span
p
caption
button
