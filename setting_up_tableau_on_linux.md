1. Pick up any old image of Windows (7+) -- I chose
[Windows 8](https://thepiratebay.gd/torrent/11116438/WINDOWS_8.1_PRO_x64-ACTIVATED(EXCELLENT))
2. [Install](https://www.virtualbox.org/wiki/Downloads) virtualbox
  * Follow [the instructions](https://www.virtualbox.org/wiki/Linux_Downloads)
  to add the `deb` to your `/etc/apt/sources.list`
  * Install `dkms`, just to be safe (assuming you've added the `deb` to your sources):
  
      ```
      sudo apt-get install dkms
      ```
  * Don't forget to download and install
  [the extension pack](http://download.virtualbox.org/virtualbox/5.0.10/Oracle_VM_VirtualBox_Extension_Pack-5.0.10-104061.vbox-extpack)
3. [Install](http://www.addictivetips.com/windows-tips/how-to-install-windows-8-on-virtualbox/)
said windows image on virtualbox
  + ***REMEMBER TO DISABLE PULSE AUDIO, BEFORE INSTALLING***
4. Boot up the windows machine, and install _Guest Additions_:
  + Goto _Devices_, _Insert Guest Additions CD image..._ 
