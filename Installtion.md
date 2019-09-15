# Installation

At the moment of deciding where Ubuntu is going to install I erased all partitions(inlcuding Windows). Once the installation is done this screen will appeared. **DO NOT PANIC IF AT RESTARTING IT FREZZES WAIT 20 SECOND AND THEN FORCE THE SHUTDOWN**

Turn it on, and Ubuntu should noramlly start check if everything is working. Now if you try to turn it off and it hangs out **DON't FREAK OUT** for what I read about is because of the graphics card, force the shutdown and use the following commands:

```
sudo apt update && sudo apt upgrade -y

ubuntu-drivers devices

sudo apt install nvidia-396
```
One way to check if is working right, go the _aditional drivers_ and choose the one of the image above
