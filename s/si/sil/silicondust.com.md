> *The following text is extracted and transformed from the silicondust.com privacy policy that was archived on 2010-05-02. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20100502030629id_/http%3A//www.silicondust.com/privacy) for the most accurate reproduction.*

# privacy - Silicondust

## HDHomeRun Lineup Server[ ¶](https://web.archive.org/web/20100502030629id_/http%3A//www.silicondust.com/privacy#HDHomeRunLineupServer "Link to this section")

Silicondust maintains a lineup server to identify and name TV channels that can be received; this information is provided as a courtesy for our users. 

Most US and Canadian cable providers do not send the name or virtual channel number of a channel along with the video stream. A channel scan will detect the channels but not be able to identify and match channels with the guide data. The purpose of the lineup server is to provide channel information for automatically matching channels with the guide data. 

When enabled: 

1) The Windows channel editor will connect to the lineup server when a channel scan is run. The list of channels is sent to the lineup server. The lineup server will identify the channels and provide channel names. 

2) When idle, the HDHomeRun will periodically perform channel scans, sending information about the channels received. This information is provided as a hash -- a unique channel identifier that allows the server to correlate channel information, providing channel names to other HDHomeRun users able to receive the same channel. It does not have the ability to detect or monitor what channels have been watched. 

**Windows:**

Lineup server support is enabled by entering the Country/Postal code and checking "Exchange channel information with the Silicondust lineup server" in HDHomeRun Setup. Lineup server support can be disabled by unchecking "Exchange channel information with the Silicondust lineup server" in HDHomeRun Setup. 

**Mac/Linux:**

Lineup server support is enabled by the following command:  
hdhomerun_config <device id> set /lineup/location <country code>:<postal code>  
Country codes: ISO Country Codes, e.g. Australia:AU, Canada:CA, Denmark:DK, Great Britain:GB, New Zealand:NZ, United States:US. 

Lineup server support can be disabled (default) with the following command:  
hdhomerun_config <device id> set /lineup/location disabled 

## HDHomeRun Support Server[ ¶](https://web.archive.org/web/20100502030629id_/http%3A//www.silicondust.com/privacy#HDHomeRunSupportServer "Link to this section")

The HDHomeRun Windows software includes an optional feature to send diagnostic information to the Silicondust support server to aid tech support. This feature is disabled by default and should only be enabled when requesting technical support. The diagnostic information may contain information such as digital TV software installed, capture devices installed, local IP address configuration, and detailed information regarding the use of the HDHomeRun. 

Communication is one-way - the support server cannot control or query information from the PC sending diagnostic information. 

Logging of diagnostic information is enabled by checking "Send diagnostic information to Silicondust support" in HDHomeRun Setup. Logging of diagnostic information is automatically disabled after 10 days of being enabled, or can be disabled at any time by unchecking "Send diagnostic information to Silicondust support" in HDHomeRun Setup. 

The diagnostic information is available to Silicondust support staff and may be kept for up to 2 months before being purged from the server. 
