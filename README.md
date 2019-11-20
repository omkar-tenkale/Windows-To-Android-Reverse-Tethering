
# Reverse-tethering-setup-Windows
### Based on: https://github.com/Genymobile/gnirehtet
One click windows to android internet connection (Opposite of Android USB Tethering)

What it does:
It helps in a situation where 
1. Phone needs internet connection.
2. PC has internet connection but doesn't have wifi/hotspot capability.
3. You have a USB cable to connect phone to pc.
4. You want to use pc's internet in your phone.

You can simply follow the steps below to get a working internet connection on your phone. 

**How to use:**
[Download this repo zip ~9MB](https://github.com/omkar-tenkale/Reverse-tethering-setup-Windows/archive/master.zip)

Extract the zip file and double click 
**START_ME_gnirehtet-autorun.cmd**

![This window will appear](help/onstart.png)

Now connect your android device to your windows pc
Select mode file transfer (not "charge only")
![This window will appear](help/charge_only_to_transfer_files.jpg)

Enable USB debugging
 (search on internet "**How to enable usb debugging in yourdevicehere**<xiaomi/samsung..>  ")
 ![This window will appear](help/enable_usb_debugging_developer_options.png)

 A prompt will appear on your phone
 
![This window will appear](help/usb_debugging_prompt.png)
 
Click OK


 App will be automatically installed on phone![This window will appear](help/client_app_install_and_start_app_with_broadcast.png
)

A vpn request dialog will appear

 ![VPN connection request](help/vpn_request.jpg)

Accept it and vpn connection will start which will provide internet connection.

 ![VPN connection started](help/vpn_started_internet_connected_indication.png)
 
 **That's it. If you see this key icon in status bar means you are connected to pc and thus internet** 



Disconnect usb after use.
![This window will appear](help/connection_starts_successfully_and_device_disconnect_after_use.png)

If this window is kept open and device connected again, the process will start automatically.No manual work needed.
Just launch once and keep minimized.
