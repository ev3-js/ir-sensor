
# ir-sensor

[![NPM version][npm-image]][npm-url]
[![Code style][standard-image]][standard-url]

get values from ev3 ir-sensor

## Installation

    $ npm install ev3-js-ir-sensor

## Usage

```js
var IRSensor = require('ev3-js-ir-sensor')
IRSensor(3).proximity
IRSensor(3).getBeacon(2)
```

## API

### IRSensor(port)

- `port` -

**Returns:**

## License

MIT

[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat
[standard-url]: https://github.com/feross/standard
[npm-image]: https://img.shields.io/npm/v/ev3-js-ir-sensor.svg?style=flat-square
[npm-url]: https://npmjs.org/package/ev3-js-ir-sensor
