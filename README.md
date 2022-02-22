# 2smart-cloud-esphome

We currently support [ESPHome 2021.10.3](https://esphome.io/changelog/2021.10.0.html#release-2021-10-3-october-27) with [extended functionality](./docs/extended.md) for 2Smart Cloud platform.

## Guides

- How to build a simple WiFi relay with ESPHome firmware in 2Smart Cloud?
    - [Russian](https://2smart.com/ru/blog/tpost/1yy4oaozh1-wi-fi-rele-s-mobilnim-prilozheniem-za-ch)
    - [English](https://2smart.com/blog/tpost/2n6ankych1-how-to-create-a-wi-fi-switch-to-control)

## Examples

- [Simple GPIO switch](./examples/blinker_with_reset_btn.yml)
- [Relay with LED](./examples/relay_with_led.yml)
- [WS2812B FastLED](./examples/ws2812b_fastled.yml)
- [GPIO switch with OTA](./examples/blinker_with_ota.yml)
- [GPIO switch with Notify](./examples/notify.yml)

## Notes

2Smart Cloud currently doesn't support ESPHome Core option `includes`, which allows to include in the main (auto-generated) sketch file for custom components, but we'll add this in future releases.
