# iOSRTMPReferenceApp

We are happy to announce that AntMedia RTMP iOS SDK is ready for developers and end-user applications.

## Prerequisites

In order to use RTMP iOS SDK, you need LFLiveKit framework build, and some other libraries for sure and Ant Media Server Enterprise Edition. Please contact us at contact@antmedia.io. We can provide Enterprise Edition for trying or personal use.

### Start the Ant Media Server Enterprise Edition

Extract the Media Server Enterprise Edition and start the server with start.sh command in the terminal:

cd /path/to/ant-media-server
./start.sh

### Project 

Extract the RTMP Reference App and open with Xcode. You may see that project has two view controllers to show: WelcomeViewController to set server ip and room name. VideoViewController to for the streaming.

No need to change anything, just run. So when you run the reference application, WelcomeViewController will be seen as initial view controller. Before tap the connect button, server id and room name should be defined. Once you define those fields, it's ready.

### How to play your stream

You may install the reference application to any other iOS device and connect to same room id or you may go to the http://localhost:5080/LiveApp/play.html?name=<room-id>, write same room id instead of <room-id>.

![Play your stream](https://i0.wp.com/antmedia.io/wp-content/uploads/2018/07/Screen-Shot-2018-07-17-at-23.39.23-1024x442.png "Logo Title Text 1")

You will see this message. So when you start streaming from Reference Application, this page will be refreshed automatically.

#### Contact

If you have any question, just send an email to contact@antmedia.io
