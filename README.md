# Rock 5 with Ubuntu 22.04 OS image
![output image]( https://qengineering.eu/github/RockUbuntu22.webp)<br/><br>
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)<br/>

------------

## Installation.

- Get a 16 GB (minimal) SD-card which will hold the image. 
- Download the `Rock5_Ubuntu22.img.xz` image (3.6 GByte) from our [Sync](https://ln5.sync.com/dl/37ffb83a0/czk9kxmj-z886httr-j45rsyip-rsix4cen) site. 
- Flash the image on the SD card with the [Imager](https://www.raspberrypi.org/software/) or [balenaEtcher](https://www.balena.io/etcher/).
- Insert the SD card in your Rock 5 and enjoy.
- Username: ***5ubuntu22***
- no password 

------------

## Tips.

* If you are in need of extra space, you can delete the opencv and the opencv_contrib folder from the SD card. There are no longer needed since all libraries are placed in the /usr/ directory.
* Use a tool like [GParted](https://gparted.org/) `sudo apt-get install gparted` to expand the image to larger SD cards. We recommend a minimum of 64 GB. Deep learning simply requires a lot of space.<br/>
* **An example of YoloV5 running on the NPU (40 FPS) is included.**

------------

## Pre-installed frameworks.

- [OpenCV](https://qengineering.eu/deep-learning-with-opencv-on-raspberry-pi-4.html) 4.8.0
- [ncnn](https://qengineering.eu/install-ncnn-on-raspberry-pi-4.html) 20230517
- NPU software [rknpu2](https://github.com/rockchip-linux/rknpu2) 1.4.0

------------

### Thanks.
A more than special thanks to [***Stuart Naylor***](https://forum.radxa.com/u/stuartiannaylor/summary), who, ever so kindly, provided us the Rock Pi 5 for free.

------------

[![paypal](https://qengineering.eu/images/TipJarSmall4.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CPZTM5BB3FCYL) 


