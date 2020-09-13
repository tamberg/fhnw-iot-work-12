# IoT Engineering
## Hands-on of lesson 12
For slides and example code, see [lesson 12](../../../fhnw-iot/blob/master/12/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Check existing forks to find the specific repository for your class.](../../network/members)*

### a) Raspberry Pi GPIO, 15'
* Use the [Grove hat](https://github.com/tamberg/fhnw-iot/wiki/Grove-Adapters#grove-base-hat-for-raspberry-pi) to connect Grove sensors to the Pi.
* Read analog values using the grove.py Python library.
* No hat? Use a [Grove jumper](https://github.com/tamberg/fhnw-iot/wiki/Grove-Adapters#grove-jumper-wires) wire to connect a sensor.
* Check the [Raspberry Pi pinout](https://pinout.xyz/pinout/wiringpi) and use 3.3V, not 5V.
* Done? Try to read a [Grove sensor with Node-RED](https://flows.nodered.org/?term=grovepi&type=node&num_pages=1).

### b) Edge gateways, 10'
* Chose one of the edge gateway projects and analyse it.
* Which protocol is used to transmit data to the cloud?
* How are updates deployed to the gateway, by whom?
* How can a proprietary local protocol be integrated?
* Be prepared to present your results.

### c) Embedded ML use cases, 10'
* Devices will know your face, voice, mood, intentions.
* Which new use cases become possible with edge ML?
* Try to take a "[thing centered](https://online-learning.tudelft.nl/courses/thing-centered-design/)" perspective, as a device.
* Be prepared to present your results.
