# Interactive 3D model viewer

Simple interactive Tiger 3D model viewer using a mobile phone in order to experiment web sockets.

## Demo

![demo gif](tiger.gif)

Try it live here : [https://tiger-viewer.herokuapp.com](https://tiger-viewer.herokuapp.com) <br/>
Notice that this app is hosted on heroku, heroku put app in sleep mode if nobody is pinging or requesting it for like 30 minutes. 
So, if nobody used this app before you, it can take 5 secondes to load the app (then the app will be awake). 

## Tech stack

* HTML / CSS
* (Vanilla) JavaScript
* DeviceOrientation Web API
* Three.js
* Node.js with socket.io

## Howto

Go to [https://tiger-viewer.herokuapp.com](https://tiger-viewer.herokuapp.com)

Once the webpage is loaded, go to [bit.ly/2G16cnk](bit.ly/2G16cnk) with your mobile phone.

After opening the link on mobile phone, wait the end of the countdown and start tilting your phone from left to right and from backwards to forwards.

(If you don't have a computer to test the app you can also visualize the 3D model with a phone or a tablet just go to [https://tiger-viewer.herokuapp.com/mobileViewer](https://tiger-viewer.herokuapp.com/mobileViewer))

## Running locally

After cloning this repo, run `node server.js`, open your browser and visit `localhost:3000`.

To be able to visit the mobile page, you'll probably need something like [ngrok](https://ngrok.com/).

Once you have ngrok installed, you'll need to run `./ngrok http 3000` and, using the urls it will give you, visit `/mobile`.

<br/><br/>

This project is based on a fork of this project : https://github.com/charliegerard/hvbrd-sockets


