# Raspberry-pi-ultrasonic-live-data-to-phone-as-message-using-Node-Red
Ultrasonic sensor is connected to the raspberry pi . This sensor values are collected in our mobile in form of messages.
This is done using Node Red.
## Node Red
Node-RED is a programming tool for wiring together hardware devices, APIs and online services in new and interesting ways.

It provides a browser-based editor that makes it easy to wire together flows using the wide range of nodes in the palette that can be deployed to its runtime in a single-click.It is build on node.js.


http://nodered.org/
## Installation of Node Red on raspberry pi

http://nodered.org/docs/hardware/raspberrypi
## Node Red on raspberry pi
  Node Red is defautly installed in  Raspbian Jessie operating system.Type the command node-red-start in the terminal.Once the node red 
  is started, point a browser at the local host which is provided.
  ![node red start](https://cloud.githubusercontent.com/assets/25893079/26528802/8a7e8fba-43d0-11e7-8e1f-d7a3de0c2402.png)
  once the Node Red is started in the browser , connect the following nodes shown below
  
![node red flow](https://cloud.githubusercontent.com/assets/25893079/26528548/6dfa1bba-43cc-11e7-8717-66799d9270a1.png)
## Creating a Twilio account
  Twilio is a Cloud communications platform for building SMS, Voice & Messaging applications on an API built for global scale. 
  https://www.twilio.com/
  Fill all the credentials , token number  and the phone number which is provied.
  ![add credentials in twilio](https://cloud.githubusercontent.com/assets/25893079/26528553/81af1804-43cc-11e7-8a5c-cb8df6f89983.png)
  Add the mobile number for which you need to get the message

![twilio](https://cloud.githubusercontent.com/assets/25893079/26528549/748334b2-43cc-11e7-8104-485d40f52e90.png)
[ultrasonic.docx](https://github.com/taditarun/Raspberry-pi-ultrasonic-live-data-to-phone-as-message-using-Node-Red/files/1034151/ultrasonic.docx)

  In the exec

![execution of exec node](https://cloud.githubusercontent.com/assets/25893079/26528557/88c006bc-43cc-11e7-8fe3-07483f04a54a.png)
![mobile message](https://cloud.githubusercontent.com/assets/25893079/26528810/c1b59a82-43d0-11e7-855c-d610b92b6d66.png)




