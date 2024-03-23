# RF demodulated bits to ESPHome transmitter raw value converter
Simple tool to convert demodulated RF bits to raw values useable by ESPHome's transmitter module

## How to use
1. Capture wireless transmission with [Universal Radio Hacker](https://github.com/jopohl/urh) - tutorial by [@hubmartin](https://www.youtube.com/watch?v=sbqMqb6FVMY)
1. Set "Show data as" to "bits"
1. Copy the bits and the Samples/Symbol into the app
1. Click convert
1. Copy the result into the "code" node in your [ESPHome config file](https://esphome.io/components/remote_transmitter#remote-transmitter-transmit-raw-action)

## [Open app](https://notisrac.github.io/RFToESPHomeConverter/)