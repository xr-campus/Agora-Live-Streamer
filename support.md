# Agora Live Streamer

This plug-in does live streaming using [Agora.io](https://www.agora.io/en/) service.

We used [Open Live](https://github.com/AgoraIO/Basic-Video-Broadcasting/tree/master/OpenLive-Android) as a reference project.

## Prerequisites

- Wifi Client Mode
- Web browser
  
## Usage

- Install this plug-in via the [RICOH Plugin store](https://support.theta360.com/uk/manual/v/content/plugin/plugin_00.html) 
- Register and start this plug-in by "[Changing the plugin](https://support.theta360.com/en/manual/z1/content/plugin/plugin_02.html)"
- When you launch this plug-in, an address information is showed in the Theta LED display. Access this address using a web browser.  
- A web UI of plug-in will be showed at your browser. Enter settings for a new streaming (described below).
- Press the "Start" button to start a new streaming.
- Statistics of current streaming will be displayed while streaming.
- Press the "Stop" botton to stop the streaming. 
- If you push the shutter button on the theta, this plug-in will start a new streaming with the previous setting.

## Settings

- Agora App ID (REQUIRED)
- Agora User ID (REQUIRED)
- Agora room name (REQUIRED)
- Frame rate (REQUIRED)
- Bit rate (REQUIRED)
- Width (REQUIRED)
- Height (REQUIRED)
- Recording volume(REQUIRED)
- Agora Token *1
- Auto restart (OPTIONAL) *2

*1
If your agora project requires the token for streaming, "Agora Token" is REQUIRED, otherwise OPTIONAL (keep empty).

*2
Because of settings of high frame rate and/or high bit rate, a sudden stop of a streaming occasionally happens. If this check is on, this plug-in will start a new streaming automatically when that occurs.


## Attention

For a stable streaming, you should set the frame rate less than 15fps and bit rate less than 2000kbps.


## Contact

xrcampus@tis.co.jp
