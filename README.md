# iot-server
An OSLC Server Node.js app that provides OSLC resources adapted from the IoT Platform.

iot-server is a Bluemix Node.js app that uses the iot-service Express.js middleware module provide an OSLC server that provides OSLC access to the IoT Platform resources. T

iot-server exploits the dynamic and asynchronous capabilities of JavaScript and Node.js to build an OSLC adapter that can easily adapt to IoT Platform resources. iot-server also uses ldp-service which optionally provides persistance capabilities using MongoDB. This allow this app to act as a mediator that integrates IoT Platform resources with other OSLC servers and domains.
