# Troubleshooting

To use many of the debugging tools, you should [join the 
RICOH THETA Plug-in Partner Program](https://www8.webcas.net/db/pub/ricoh/thetaplugin/create/input).
This will allow you to use the Ricoh Desktop Application to put the THETA into
*Developer Mode*. With developer mode enabled, you can use adb and Vysor to get
more information on your camera.

## Find IP Address of Camera

The recommended may to find the IP address of the camera is to use the official Ricoh mobile app
and connect the mobile app to the camera with client mode. If you prefer to use 
a different method, here are 5 alternative ways to find the IP address.

1. Log into your WiFi router and check which IP was assigned to your THETA V using DHCP
2. If your THETA V is enabled with “Developer Mode”, use `adb shell` to log into your camera and then use ifconfig to find the IP address.
3. Use Vysor to check the IP address. Requires “Developer Mode”.
4. Use [dns-sd](https://community.theta360.guide/t/developing-theta-client-mode-applications/2450/16?u=codetricity) (does not require Developer Mode)
5. Use [Python scripts](https://youtu.be/z_9elAmeXv4)

### adb

Using adb shell to find IP address and test Internet access.

![](/main/img/troubleshoot/ip/adb-shell.png)

![](/main/img/troubleshoot/ip/ifconfig.png)

In the example above, the IP address of my camera is 192.168.2.102.

### Vysor

Using Vysor to get IP address of THETA V.

![](/main/img/troubleshoot/ip/phone-status.png)

![](/main/img/troubleshoot/ip/ip-address.png)


## Plug-in Permissions

Use Vysor to check the permissions of your plug-in.

*Settings -> Apps*

![](/main/img/troubleshoot/permissions/apps.png)

Go to the app you want to verify.

![](/main/img/troubleshoot/permissions/wireless.png)

Make sure the appropriate permissions are set. Most plug-ins will need access to the
camera of the THETA.

![](/main/img/troubleshoot/permissions/camera.png)

