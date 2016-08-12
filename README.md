![Mote](mote-logo.png)

Buy the Mote controller & accessories here: https://shop.pimoroni.com/products/mote

##Installation

###Windows/Linux/Mac

Install the mote library with pip, like so:

```
pip install mote
```

If while trying to execute the exemple you get the following error: 'ImportError: No module named serial'.
They you neet to also install the Python Serial library, like so:
```
pip install pyserial
```

###Raspberry Pi (Raspbian)

We've created a super-easy installation script that will install all pre-requisites and get your Mote up and running in a jiffy. To run it fire up Terminal which you'll find in Menu -> Accessories -> Terminal on your Raspberry Pi desktop like so:

![Finding the terminal](terminal.jpg)

In the new terminal window type:

```bash
curl -sS get.pimoroni.com/mote | bash
```

If you choose to download examples you'll find them in `/home/pi/Pimoroni/mote/examples`.

