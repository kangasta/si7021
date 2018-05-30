# py-si7021

Library for playing around with si7021 relative humidity and temperature sensor with Raspberry Pi. Based on [pigpio example](http://abyz.me.uk/rpi/pigpio/examples.html#Python_Si7021_py).

## Usage

## Testing

Run unit tests with command:

```bash
python3 -m unittest discover -s tst/
```

Get test coverage with commands:
```bash
coverage run -m unittest discover -s tst/
coverage report -m
```