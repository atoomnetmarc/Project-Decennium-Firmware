This is the firmware for this PCB: https://github.com/atoomnetmarc/Project-Decennium

# OTA Password

Copy `local_env-example.ini` to `local_env.ini` and fill in your own `hostname` and `ota_password`.

# Compile and uploading firmware

Compile firmware with `platformio`. I used `Visual Studio Code` with the `PlatformIO` extension.

You must also upload the firmware with `platformio`.

# Wi-Fi configuration

When no Wi-Fi configuration is known then the firmware will start an access point on SSID `decennium-`-something. Connect to it, then open http://192.168.4.1

When configured, pressing reset twice will also start the access point.
