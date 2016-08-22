# TelePresence-on-Android
Explore one of the many ways to get P2P video on Android. This time using Intel's Xwalk-WebRTC package.

This tutorial is what I have followed to get a webRTC video-chat running on two android devices. 
https://crosswalk-project.org/#documentation/webrtc

The output of the python command in section "Run Android with Crosswalk" is what generates ".java" files and the
APK out of the Javascript code. The Java files look like the examples in this link
( https://crosswalk-project.org/#documentation/embedding_crosswalk ). Most of the work I did after that is specific to our
smart-glasses ( pick up the right microphone , show dialogs etc , which require further modifications to existing JS and Java 
files).

This project requires a Linux machine ( or a VMware linux image ) to run the signaling server
IP configurations ( both peers need to be able to access the server ). This was a bit of pain on the borrowed work machine 
with the VMware image. Had to use a Ethernet to USB adapter to get VMware Ubuntu image to expose it's IP address to outside
world.

