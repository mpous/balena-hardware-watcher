
# Bird Watcher using Edge Impulse Linux SDK and BalenaOS

This project enables you to run Edge Impulse Linux SDK on balenaOS thus allowing you to manage a fleet of devices with the same software stack on them which can do various kinds of on-device Machine Learning applications. 

### Hardware 
<table>
<tr><td>
<img height="24px" src="https://files.balena-cloud.com/images/fincm3/2.58.3%2Brev1.prod/logo.svg" alt="fincm3" style="max-width: 100%; margin: 0px 4px;"></td><td> balenaFin</td>
</tr>
<tr><td>
<img height="24px" src="https://files.balena-cloud.com/images/raspberrypi3/2.58.3%2Brev1.prod/logo.svg" alt="raspberrypi3" style="max-width: 100%; margin: 0px 4px;"></td><td>Raspberry Pi 3 Model B+</td>
</tr>
<tr><td>
<img height="24px" src="https://files.balena-cloud.com/images/raspberrypi4-64/2.65.0%2Brev1.prod/logo.svg" alt="raspberrypi4-64" style="max-width: 100%; margin: 0px 4px;"></td><td>Raspberry Pi 4 Model B</td>
</tr>
</table>

 [Raspberry Pi camera](https://www.raspberrypi.org/products/camera-module-v2/) or any USB camera.

### Software 

* Sign up for a free [Edge Impulse account](https://edgeimpulse.com/)
* Sign up for a free [BalenaCloud account](https://www.balena.io/)
* [balenaEtcher](https://www.balena.io/etcher/)

### Deploy using balenaCloud

Click on the *deploy-with-balena* button as given below, which will help you to deploy your application to balenaCloud and then to your Raspbery Pi in **one-click!**

[![](https://balena.io/deploy.png)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/just4give/balena-ei-linux-bird-watcher)

Else you can build your own release by cloning this repo on your primary machine (x86) and use the following commands :
```
$ git clone https://github.com/just4give/balena-ei-linux-bird-watcher.git
$ cd balena-ei-linux-bird-watcher
$ balena login
$ balena push balena-ei-linux-bird-watcher 
```

### Data Collection Mode

Set the variable to 1 which will bring the application to data collection mode. 
```
EI_COLLECT_MODE_IMAGE
``` 
and follow the instructions being laid down in the terminal.

### 3D Print
Download STL files from here [bird_watcher_3D_print.zip](https://github.com/just4give/balena-ei-linux-bird-watcher/files/7095446/bird_watcher_3dprint.zip)

