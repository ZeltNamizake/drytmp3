# DRYTMP3
DRYTMP3 - Youtube Downloader MP3 for Termux Android
and this is made using Javascript, Nodejs, API, and some packages or modules

#### Install in Termux
* Setup Storage
  ```bash
  termux-setup-storage
  ```
* Update and Upgrade
  ```bash
  apt update && apt upgrade -y
  ```
* Install Packages
  ```bash
  apt install ffmpeg nodejs git
  ```
* Open Directory and Install Modules
  ```bash
  cd drytmp3 && npm install axios https fluent-ffmpeg
  ```
* Run script for download audio
  ```bash
  #example
  node drytmp3 https://youtu.be/.....>
  ```

###### Created by  ```Driyasz (ZeltNamizake)```
