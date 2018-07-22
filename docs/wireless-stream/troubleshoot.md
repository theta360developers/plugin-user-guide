# Troubleshoot Wireless Live Streaming

## Testing Plug-in with Vysor

As of version 1.04, plug-in information can be viewed in Vysor. To use Vysor, you
need to [join the 
RICOH THETA Plug-in Partner Program](https://www8.webcas.net/db/pub/ricoh/thetaplugin/create/input).

Although using Vysor with the plug-in is not an official supported feature, 
it is useful for debugging, especially if the stream is not appearing on 
YouTube and you’re wondering what’s going on in the camera.  In additional to the plug-in 
settings, you can also see the live stream on the camera. 


I’ve translated the major sections for you into English. Note that I have low bandwidth in my office and have the resolution and bitrate set very low for my test. Please set your own resolution and bitrate to the highest value that your network can support.

![](/wireless-stream/img/troubleshoot/vysor-english.png)

This is the original Japanese.

![](/wireless-stream/img/troubleshoot/vysor-japanese.png)

The view is in equirectangular format. It's a quick way to
make sure the video stream is being managed by the plug-in.

![](/wireless-stream/img/troubleshoot/equirectangular-view.png)

## Resolution Error

You may see an error about the resolution being not supported
in a current configuration. In my tests, the live streaming still works.

### Error Message
![](/wireless-stream/img/troubleshoot/resolution-error.png)

### Actual Results
The error message above does not seem to impact use of the plug-in.
The image is blurry due to poor upstream bandwidth at my test location.

![](/wireless-stream/img/troubleshoot/still-working.png)

![](/wireless-stream/img/troubleshoot/working-2.png)


