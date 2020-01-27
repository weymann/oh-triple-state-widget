# Openhab Triple State Widget
Widget for Openhab reflecting 3 states for a certain item. Underlying problem is that most of my Smarthome items can have a
* "good" state
* "bad" state
* but also can have an "undefined" state

Example:
Battery state can be ok or low, but if battery is empty or the device isn't reachable another state can be displayed. Therefore you can define 
the good and bad state and in case of undefined an alert sign is displayed.
The defined icons needs to be part of [font awesome] (https://darksky.net/dev) which can be easily installed in openhab environment 