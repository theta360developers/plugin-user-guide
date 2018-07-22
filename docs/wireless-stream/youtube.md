# YouTube Live 360° Event

If your THETA is not connected to the Internet or you do not know the IP address,
refer to the Camera Configuration section of this guide.

Once you have the IP address, you can now use any web browser to to configure your THETA V for YouTube Live Events.

## Connect browser to RICOH THETA V

Use port 8888

My THETA V was assigned an IP address of 192.168.2.100. I’m pointing my browser to 192.168.2.100:8888. This is the IP address and port for a configuration web server that is running on your THETA V.

In your browser, you will see the configuration tool below. You will need to fill in the 
*Server URL* and the 
*Stream name/key* with the information from your YouTube Live Event.

![](/wireless-stream/img/youtube/streaming-server.png)

## Set Up YouTube Live Event

There is extensive information on setting up a YouTube Live 360 Event in the 
[RICOH THETA Live Streaming Guide](http://theta360.guide/community-document/live-streaming.html). 
Although the guide is for the RICOH THETA S, 
most of the information is still relevant for the RICOH THETA V.

I’ll cover some of the settings in this guide. Note that I have slow upstream bandwidth in my office and the screenshots show lower resolution and bandwidth settings. You should use the highest settings that your Internet connect supports. The default settings are 4K(3840x1920) 30fps with a bit rate of 20Mbps.

## YouTube Live Event Settings

Make sure you create a Live Event.

![](/wireless-stream/img/youtube/advanced-settings.png)

You need to click on *Advanced Settings* and look for *This live stream is 360°*.

![](/wireless-stream/img/youtube/360-event.png)

On the Live Events setting page, you can get the Stream Name and Server URL. Copy and paste this information into the Wireless Live Streaming plug-in configuration application. Make sure you are using a reusable stream key.

![](/wireless-stream/img/youtube/events.png)

![](/wireless-stream/img/youtube/stream-key.png)

### Managing Streams
You may need to adjust the stream sustained bitrate to match your Internet
bandwidth.  To create a new stream, select the drop-down menu box
below the *Resuable stream key*.

![](/wireless-stream/img/youtube/new-stream.png)

You may see an error about the resolution not matching the configuration. In my tests,
I ignored the error message and the stream still worked fine.

The error message was:

> You need to change the video resolution.  The current resolution
is (640x320), which is not supported for this configuration. The
expected video resolution is (854x480).

 If you are still having problems, you can also try the Variable bitrate. 
Although this is in BETA, the setting worked in my tests except for a 
black circle at the top and bottoms of the streams. It's better to
specify a bitrate. I've used  4K, 2K, and 480 bitrates successfully. In the 
partially successful test below,
I am using 4K 30fps with variable bitrate.

![](/wireless-stream/img/youtube/variable-beta.png)

### Server Information

Copy the server information to your plug-in configuration web-based tool.

![](/wireless-stream/img/youtube/server-info.png)

## Start the Stream

Your moment of glory has finally arrived. Start the stream.  You can press the shutter button of your THETA V to start the stream or press the Start streaming button in the web interface. After this initial configuration, you should be able to use the THETA V as a standalone device for live streaming.

In the web browser plug-in configuration, you'll see the word
*Streaming* with a red dot next to it.  You should have the correct
*Server URL*  and *Stream name/key* that you copied from YouTube.

![](/wireless-stream/img/start/key-filled.png)

The *Start streaming* button will change to a *Stop streaming* button.

![](/wireless-stream/img/start/stream-working.png)

If you want to preview your 360 video stream prior to going live, press
*Preview Stream* in the YouTube Live Control Room.  In the example below,
I am using a variable resolution stream. However, you can set it to 
a specific resolution and bitrate using the YouTube presets.

![](/wireless-stream/img/start/variable-resolution.png)

In the YouTube Live Control Room, make your event Live.

![](/wireless-stream/img/start/youtube-site.png)



### View on YouTube
It works!

![](/wireless-stream/img/start/youtube-view.png)

Test from other browsers. Rotate the video feed. Share
with your millions of followers. :-)

![](/wireless-stream/img/start/rotate-view.png)

