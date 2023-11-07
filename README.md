# 2smart-cloud-esphome

We currently support [ESPHome 2021.10.3](https://esphome.io/changelog/2021.10.0.html#release-2021-10-3-october-27) with [extended functionality](./docs/extended.md) for 2Smart Cloud platform.

## Guides

- [How to assemble the simplest Wi-Fi temperature and humidity sensor](https://2smart.com/docs-resources/tutorials/how-to-assemble-the-simplest-wi-fi-temperature-and-humidity-sensor-in-30-minutes)
- [How to build a simple WiFi relay with ESPHome firmware in 2Smart Cloud](https://2smart.com/docs-resources/get-started/how-to-create-a-wi-fi-switch-to-control-via-a-mobile-app-and-telegram-bot)
- [ESPHome-based LED strip controller: a smart device without programming](https://2smart.com/docs-resources/tutorials/esphome-based-led-strip-controller-a-smart-device-without-programming)
- [Simple ESP32-based alarm with ESPHome firmware](https://2smart.com/docs-resources/tutorials/simple-esp32-based-alarm-with-esphome-firmware)

## Examples

- [Simple GPIO switch](./examples/blinker_with_reset_btn.yml)
- [Relay with LED](./examples/relay_with_led.yml)
- [WS2812B FastLED](./examples/ws2812b_fastled.yml)
- [GPIO switch with OTA](./examples/blinker_with_ota.yml)

## Notes

2Smart Cloud currently doesn't support ESPHome Core option `includes`, which allows to include in the main (auto-generated) sketch file for custom components, but we'll add this in future releases.
