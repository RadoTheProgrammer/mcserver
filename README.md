## 1. Setup the minecraft server

This repository is the template of a minecraft server configured with craftbukkit and the RaspberryJuice plugin, especially useful when using the library `mcpi` 

This repository contain the data for a minecraft server, you can clone it:

```

git clone https://github.com/RadoTheProgrammer/mcserver
cd mcserver
```

## 2. Run

In your server directory, run `start.bat` if you're on Windows, or `start.sh` on linux, `start.command` on mac, ensure giving the permissions to use the executable.

Then you can go to the minecraft server in the ip address `localhost`

## 3. mcpi


Now, you can use `mcpi` library to interact with it, [install python](https://www.python.org/downloads/) and mcpi with `pip install mcpi` and make a hello world program.

```python

from mcpi.minecraft import Minecraft
mc = Minecraft.create()
mc.postToChat("Hello World")
```
