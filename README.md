# CometD demos

[CometD](http://cometd.org/) is a scalable web event routing bus that allows you to write low-latency, server-side, event-driven web applications. 

This image can be used to run the CometD demo applications. Which is useful if you want to take a quick look at the CometD Demos and if you are prototyping/experimenting with CometD client applications.

The CometD Demos contain:
* Four full chat applications (one developed with vanilla Javascript, on with Dojo, one with jQuery and one with Angular 1).
* Examples of extensions such as message acknowledgement, reload, timesync and timestamp.
* An example of how to echo private messages to a particular client only.
* A clustered auction demo (using the Oort clustering).

## How to use this image
The web server is exposed on port `8080`. To run the demos in background, use the following command.

`$ docker run -d --name cometd-demos -p 8080:8080 robertmrk/dh-test`

You can view the demos by visiting `http://localhost:8080`.
