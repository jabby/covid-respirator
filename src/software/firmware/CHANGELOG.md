# Changelog

## v1.3.1

- use the green LED near the start button to show whether the breathing mode is ON or not
- disable alarms related to the breathing cycle when program is stopped
- fix an issue with a battery alarm being briefly triggered at every boot
- integration test: open both valves at startup

## v1.3.0

- add a program to test integration
- support electronic hardware v1 **and** v2
  (_v1 by default, v2 through a config flag_)
- implement start/stop
  (_from now on, machine will begin stopped!_)
- handle Emerson valves
  (_through a config flag_)
- improve the way buzzer is controlled

## v1.2.3

- fix an issue with buzzer (sometimes it was stuck buzzing whereas no alarm were triggered)
- add battery-related alarms

## v1.2.2

- handle several pneumatic systems
  _(for the first 2 working typologies of prototype)_

## v1.2.1

_Unreleased_

## v1.2.0

First release version