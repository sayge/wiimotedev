## Wiimotedev Project ##
Wiimotedev Project is to show what really can be done with wiiremotes (not proof-of-concept!). The main project wiimotedev-daemon is created especially for developers. If you want wiiremote support in your application go and check my project!

Adventages:
  * an elegant way to add wiiremote support in your application
  * wiiremotes can be easily shared by large amounts of applications
  * **very simple api, just run and check by qdbusviewer.**
  * support :)
This project include also:
  * wiimotedev-io
  * wiimotedev-toolkit
  * wiimotedev-examples
Projects that use wiimotedev-daemon:
  * [Clementine Player](http://code.google.com/p/clementine-player)
  * Plasma Media Center (under development)

## Wiimotedev Daemon ##

Wiimotedev-daemon is a core project in wiimotedev family. It works on dbus system layer, provides a full set API to communicate with wiiremotes. Service brings two interfaces, one for general communication with wiiremote(s), the other for service management. In other words this service manages wiiremotes connections and brings API to communicate with wiiremotes directly.

## Wiimotedev Toolkit ##
Wiimotedev-toolkit is a Qt4 Front-end for wiimotedev service. This is simple hardware monitor, you can use this for get low level informations from wiimote/nunchuk/classic hardware.

http://www.youtube.com/watch?v=oX04xmjqvGE

![http://wstaw.org/m/2012/12/30/wiimotedev-toolkit-1.4.2.png](http://wstaw.org/m/2012/12/30/wiimotedev-toolkit-1.4.2.png)

## Wiimotedev Examples ##
Wiimotedev-car-example – example how wiimotedev-daemon dbus interface works. It’s modified version of remotecontrolledcar from qt4 qdbus examples. If you want wiiremote support in your application check it.

![http://wstaw.org/m/2012/12/30/wiimotedev-car-example-1.4.2_1.png](http://wstaw.org/m/2012/12/30/wiimotedev-car-example-1.4.2_1.png)