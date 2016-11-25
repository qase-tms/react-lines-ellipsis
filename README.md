[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

# react-lines-ellipsis

Poor man's multiline ellipsis component for React.JS

### Installation

To install the stable version:

```
npm install --save react-lines-ellipsis
```

## Usage

```xml
<LinesEllipsis
  text="long long text"
  maxLine="3"
  ellipsis="..."
  trimRight
/>
```

## Limitations

- only accept plain text
- can be fooled by `::first-letter` styles
- require some es2015 methods: `Array.from`, `Object.keys`, etc.

## Dev TODO

- [ ] demo page
- [ ] test cases
- [ ] improve performance
