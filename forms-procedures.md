# Forms and procedures
----

## Technical Data Collection Notes

Speech audio was recorded at a sampling rate of 48 kHz, in stereo 16 bits PCM WAV files, 
with each user panned hard left or hard right. Also, the audio output of each VR app was 
recorded for layering in analysis files. Video data included two camera perspectives in 
each room (front and back), screen capture for each users’ HMD view, and the server 
overview that displays the VE with both avatars. Video recordings were made at 50 frames 
per second, 1920 x 1080 pixels. The Lab Streaming Layer (LSL) is a system for the unified 
collection of time-series data in research experiments that handles networking and 
time-synchronization of data collection [1]. The LSL application suite was used to 
collect log data from the HMD, controllers, and tracker Transforms. Additionally, custom 
interface events were collected in the VR app and streamed to the LSL data recorder. Data 
from the VR headset and controllers were collected at 200 Hz. The LSL data collection 
architecture can be seen below.

<img src="/assets/images/invokeDataStreams.jpg" width="461" height="372" alt="LSL data collection 
architecture">


## References

[1] Christian Kothe, Chadwick Boulay, and Tristan Stenner. Lab streaming layer (LSL).
San Diego, USA, 2019. url: https://github.com/sccn/labstreaminglayer.

