# Multisensor Tracking

This project is a functional example demonstrating the implementation of the Samsung Health Sensor API for Wear OS.

## 🚀 Releases & Downloads

* **Latest Release**: [v.1.0.0](https://github.com/dcuevasa/galaxy-watch-health-sensors-example/releases/tag/v.1.0.0)
* **Direct APK Download**: [app-debug.apk](https://github.com/dcuevasa/galaxy-watch-health-sensors-example/releases/download/v.1.0.0/app-debug.apk)

## Source Codelab

This code is based on the official Samsung Codelab:
[Track Blood Oxygen Level and Heart Rate Using Samsung Health Sensor API](https://developer.samsung.com/codelab/health/blood-oxygen-heart-rate.html#)

## Requirements

To build and run this project, you need the Samsung Health Sensor API `.aar` library file (`samsung-health-sensor-api-1.4.1.aar`). 

Since it is ignored in version control, you must download it manually and place it in the `app/libs/` directory of the project.

- **Direct Download Link to `.aar`**: [Download samsung-health-sensor-api-1.4.1.aar](https://developer.samsung.com/SHealth/file/13ab7f19-be94-4b52-917f-34dd688cf857)
- **Overview and Other Examples**: [Samsung Health Sensor API Overview](https://developer.samsung.com/health/sensor/overview.html)

## Enabling Developer Mode for Health Platform

Go to Settings > Apps > Health Platform on your watch.

Find the words "Health Platform" (the actual title text) at the very top of that menu.

Quickly tap that title text about 10 times.

### Verification
You will know it worked when the text [Dev mode] appears directly below the "Health Platform" title. If you ever need to turn it off, you simply tap the title 10 times again until the tag disappears.
