# [`firmware-circuitpython-esp32`](https://github.com/spectrachrome/firmware-circuitpython-esp32)

**Please note I'm currently focussing on the [Rust-based ultra-wideband firmware](https://github.com/spectrachrome/firmware-rust-esp32-uwb) since it's the most promising option for game modes which depend on precise ranging.

This repository contains firmware written in CircuitPython for ESP32 controllers used in the LEDswarm project. Drivers are set up to support the [ADXL343 accelerometer](https://www.analog.com/en/products/adxl343.html), although any ADXL34x device can be used.

## Dependencies

The following dependencies are needed for the project to work correctly:

* [`adafruit_bus_device`](https://github.com/adafruit/Adafruit_CircuitPython_BusDevice)
* [`adafruit_adxl34x`](https://github.com/adafruit/Adafruit_CircuitPython_ADXL34x)

Note that these are already set up in the [`lib`](https://github.com/spectrachrome/firmware-circuitpython-esp32/tree/main/lib) folder of this repository. You may also install any desired version yourself by manually putting it into the `lib` folder of your `CIRCUITPY` drive.
