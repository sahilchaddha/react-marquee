# SC-react-marquee [![npm version](https://badge.fury.io/js/react-marquee.svg)](http://badge.fury.io/js/react-marquee)

A plain old `<marquee>` tag replacement in React component.

This is a forked branch.

All Credits goes to jasonslyvia/react-marquee.

This forked branch fixes a specific issue of Offset not getting to reset to 0 after text change.

Release Notes :

1.Added Support for Dynamic Text Changes.

## Installation

### Via Package.json

```
"react-marquee": "https://github.com/sahilchaddha/SC-react-marquee.git"
```

## Usage

```javascript
var ReactDOM = require('react-dom');
var Marquee = require('react-marquee');

ReactDOM.render(
  <Marquee text="this is a very very very very very very very very very very very very very very very very long text" />
, document.body);
```

## Props

### text

Type: String Default: `""`

The text displayed in marquee.

### hoverToStop

Type: Bool Default: `false`

By default, only hover makes the marquee move.

### loop

Type: Bool Default: `false`

Whether or not loop the marquee.

### leading

Type: Number Default: `0`

The leading waiting time for the marquee to move.

### trailing

Type: Number Default: `0`

The trailing waiting time for the marquee to start over.

## Scripts

```
$ npm run build
```

## License

MIT
