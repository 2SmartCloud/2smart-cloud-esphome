# Extended functionality

## Binary sensor platforms

2Smart Cloud platform currently support all platforms from ESPHome with additional `reset_sensor` which is a extended [gpio platform](https://esphome.io/components/binary_sensor/gpio.html) with single functionality - reset users credentials to connect device to another account.

## Pairing mode

Extended functionality added in `captive_portal` that allows pair devices via 2Smart Cloud mobile app.

## Notifications

```notify``` - is a method made to comfortably manage notifications instead of ```publish_json```. You can use it like:
```
on_...:
  then:
	  - mqtt.notify:
		  payload: |-
			  root["logLevel"] = "info";
			  root["message"] = "DEVICE TURN ON";
```
where ```root["logLevel"]``` is the logging level, it can be "error", "warn", "info"