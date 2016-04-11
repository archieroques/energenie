# energenie
Python module to easily control the Energenie power sockets with Pi-mote addon board from a Raspberry Pi (all versions). 

The board is available with two sockets for £20 from Pimoroni: https://shop.pimoroni.com/products/pi-mote-control-starter-kit-with-2-sockets

There is some basic software available here: https://energenie4u.co.uk/res/software/ENER002-2PI.py , but it just relies on the user hitting the enter key to turn on sockets in turn. This is a module which reuses some of that code, but makes it easier for it to be used in existing programs. 

The three functions are:
energenie.on(socket_number)
energenie.off(socket_number)
energenie.changestate(socket_number, state) where state is a boolean variable (True/False).

It's a good idea to setup your sockets as described in Energenie's instructions (https://energenie4u.co.uk/res/pdfs/ENER314%20UM.pdf).
