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
* Hands-on, 10': Embedded ML use cases
* Devices will know your face, voice, mood, intentions.
* Which new use cases become possible with edge ML?
* Try to take a "[thing centered](https://online-learning.tudelft.nl/courses/thing-centered-design/)" perspective, as a device.
* Be prepared to present your results.

### Submitting results
* [Commit and push](#git) local changes to your repository.
* Want a review? [Create an issue](../../issues/new), mention me (@tamberg).

## Tools
### Git
On your computer
* In the hands-on repository [fork for your class](../../network/members), in README.md, click the _GitHub Classroom link_.
* Once you accept the assessment, you get a personal, private repository URL for your _USER_NAME_:<pre>
http://github.com/fhnw-iot-CLASS/fhnw-iot-work-12-USER_NAME</pre>

On your computer or Raspberry Pi
* Clone the repository<pre>
    $ cd ~
    $ git clone REPO_URL</pre>
* Add a file<pre>
    $ git add FILE</pre>
* Commit changes<pre>
    $ git commit FILE -m "Fixed all bugs"</pre>
* Push changes<pre>
    $ git push</pre>

## Wiki
- [IoT Engineering Wiki](https://github.com/tamberg/fhnw-iot/wiki)

## Support
- [IoT Engineering Slack](https://fhnw-iot.slack.com/)
