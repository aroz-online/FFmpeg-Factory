![](image/0.jpg)
# FFmpeg-Factory
The FFmpeg GUI for the ArOZ Online System

## DEPRECATED
This module is no longer usable in the latest [ArozOS 1.0](https://github.com/tobychui/arozos) Builds. The FFmpeg Factory has been included in the offical build of ArozOS 1.0. Hence, this repo is archived and no further development will be done to this version of FFMpeg Factory.

## Installation
The installation instruction below assume you have already got [ArOZ Online System](https://github.com/tobychui/ArOZ-Online-System) installed.

## Demo 
See the system demo in this [Youtube Video](https://www.youtube.com/watch?v=eCKVFfYGJfs&feature=youtu.be) 

### Manual Installation
1. Install ffmpeg via the command ```sudo apt-get install ffmpeg```. On older version of Debian, you might use libav instead of ffmpeg.
2. Download the repo as a zip file and then unzip the ```module/FFmpeg Factory``` into your ArOZ Online System Root (AOR).
In most cases, the module should be located at ```/var/www/html/AOB/FFmpeg Factory``` after unzip.

### Install via Module Manager (WIP)
1. Copy and paste this Github repo URL into the Module Manager
2. Click Install and wait for the process to finish.

## Screenshots
![](image/1.png)

Main interface for the FFmpeg Factory

![](image/2.png)

Number of task to convert in parallel can be adjusted in the Setting menu.

![](image/3.png)

To add file, either click the "Add File" button on the menu bar or drag and drop files from File Explorer into the FFmpeg interface.

## License
MIT. See the LICENSE file for more information.
*FFMpeg is not part of this project. Please refer to the [FFmpeg Github repo](https://github.com/FFmpeg/FFmpeg) for more information.*
