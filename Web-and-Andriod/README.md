This repo includes the code for the esp32-C3-DEVKITC-02 that fits into the MIT NSE Geiger counters. It also includes a web app and andriod app that currently work.

we use gpio 4 on the esp

You may have to do some things to make the web app work on google (will add more about this when making tutorial of how to use everything)


## How to use Andriod App with Esp-32 Geiger counter

1. Ensure correct code is uploaded to esp-32, the code in the directory phone-things/esp-32-code-for-geiger-app
if you need help with this refer to the uploading section here https://randomnerdtutorials.com/installing-esp32-arduino-ide-2-0/
2. Install android studio, open the app's code (hosed in phone-things/SimpleBluetoothTerminal) generate an apk, then load it on to your phone.
3. Open the app, turn on the geiger counter, and pair


## How to use Web App with Esp-32 Geiger counter
(chrome specific guide, although other browsers may work too)


1. Ensure correct code is uploaded to esp-32, ie the code in the directory web-things/esp-32-code-for-geiger-website, this directory itself is in thek directory
if you need help with this refer to the uploading section here https://randomnerdtutorials.com/installing-esp32-arduino-ide-2-0/
2. Enable experimental features. to do this go to the search bar and type about://flags press enter and you should come to an experimental features area.

Enable all of these:

Experimental Web Platform features
#enable-experimental-web-platform-features

Web Bluetooth
#enable-web-bluetooth

Use the new permissions backend for Web Bluetooth
#enable-web-bluetooth-new-permissions-backend

Web Bluetooth confirm pairing support
#enable-web-bluetooth-confirm-pairing-support

3. Open index.html locally, or upload it to some server, click connect


Thank you to Rui & Sara Santos, Kai morich, and Neil Kolban for providing example code to work from
