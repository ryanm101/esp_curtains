# ESP (TYWE3S) Curtains Teardown and Custom Firmware

This project is to intergrate a set of Wifi Controlled curtains based on the Chinese Smart Home App.

The App is hosted on chinese servers and requires a login to be created. This project is to replace the chinese firmware with:

1. Tasmota
or
2. ESPHome
or
3. A custom firware that will be able to be integrated with Home assistant

## Process

1. was the teardown as per [Notes.md](Notes.md), this included identifying the RX/TX pins and getting a copy of the firmware off the chip.
2. Install the app on a phone and watch how the curtains worked.
3. Use a breadboard to split out the pins so that we can Listen to the communications and see if based on app button presses we can mimic and replay the commands.
