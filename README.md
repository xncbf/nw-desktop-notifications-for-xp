https://github.com/robrighter/nw-desktop-notifications  
I made this repository for xp of the above project

##NW Desktop Notifications

A simple system for creating desktop notifications for [node-webkit](https://github.com/rogerwang/node-webkit) applications.


##Usage

By including nw-desktop-notifications.js and nw-desktop-notifications.html in your project you can create desktop notifications for your application by calling:

	window.LOCAL_NW.desktopNotifications.notify(iconUrl, title, content, clickHandlerCallback);


##Running the demo  
(0) download nw on https://dl.nwjs.io/v0.14.7

(1) Clone this project

(2) cd into the project

(3) Run the nw application

	nw .

(This assumes you have nw aliased to node-webkit)

	alias nw='~/Applications/node-webkit.app/Contents/MacOS/node-webkit'


##Update the Look-and-Feel

You can update the look and feel of the desktop notifications by updating the css embedded (via style tag) in nw-desktop-notifications.html.