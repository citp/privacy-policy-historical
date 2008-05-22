> *The following text is extracted and transformed from the silicondust.com privacy policy that was archived on 2008-05-22. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20080522131112id_/http%3A//www.silicondust.com/wiki/privacy) for the most accurate reproduction.*

# privacy - Silicondust

## HDHomeRun Lineup Server[ ¶](https://web.archive.org/web/20080522131112id_/http%3A//www.silicondust.com/wiki/privacy#HDHomeRunLineupServer "Link to this section")

Silicondust maintains a lineup server to identify and name TV channels that can be received, this information is provided as a courtesy for our users. 

Most US and Canadian cable providers do not send the name or virtual channel number of a channel along with the video stream. A channel scan will detect the channels but not be able to identify and match channels with the guide data. The purpose of the lineup server is to provide channel information for automatically matching channels with the guide data. 

Windows: connection to the lineup server is enabled by ticking "Connect to the Silicondust lineup server" in HDHomeRun Setup. 

When enabled: 

1) The Windows channel editor will connect to the lineup server when a channel scan is run. The list of channels is sent to the lineup server. The lineup server will identify the channels and provide channel names. 

2) When idle, the HDHomeRun will periodically perform channel scans, sending information about the channels received. This information is provided as a hash -- a unique channel identifier that allows the server to correlate channel information, providing channel names to other HDHomeRun users able to receive the same channel. It does not have the ability to detect or monitor what channels have been watched. 

Connection to the lineup server can be disabled by unticking "Connect to the Silicondust lineup server" in HDHomeRun Setup. 

## HDHomeRun Support Server[ ¶](https://web.archive.org/web/20080522131112id_/http%3A//www.silicondust.com/wiki/privacy#HDHomeRunSupportServer "Link to this section")

The HDHomeRun Windows software includes an optional feature to send diagnostic information to the Silicondust support server to aid tech support. This feature is disabled by default and should only be enabled when requesting technical support. The diagnostic information may contain information such as digital TV software installed, capture devices installed, local IP address configuration, and detailed information regarding the use of the HDHomeRun. 

Communication is one-way - the support server cannot control or query information from the PC sending diagnostic information. 

Logging of diagnostic information is enabled by ticking "Enable connection to Silicondust support server" in HDHomeRun Setup. Logging of diagnostic information is automatically disabled after 10 days of being enabled, or can be disabled at any time by unticking "Enable connection to Silicondust support server" in HDHomeRun Setup. 

The diagnostic information is available to Silicondust support staff and may be kept for up to 2 months before being purged from the server. 
