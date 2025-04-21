# MeowFace Tracking Module

> Let VRCFaceTracking take advantage of **MeowFace**'s tracking directly from your Android device.

## Installing **MeowFace Tracking Module** for **VRCFaceTracking**.

[Latest Release](https://github.com/Sparkpy/VRCFaceTracking-MeowFace/releases/tag/Release)

* VRCFaceTracking Module Registry
  * Install **MeowFace Tracking Module** by looking it up in the **Module Registry** and installing directly!
  
* Manual
  * Include the supplied **.dll** release in `%appdata%/VRCFaceTracking/CustomLibs`. 
  
**VRCFaceTracking is required to use MeowFace Tracking Module.**
  
## Using MeowFace with VRCFaceTracking

1. Download **MeowFace** from [Itch.io](https://suvidriel.itch.io/meowface)
2. Initialize `MeowFaceExtTrackingInterface` in the **VRCFaceTracking** app.
3. Use the information provided from **VRCFaceTracking** to configure **MeowFace** to properly send the data.

## Troubleshooting

> MeowFace is not connecting to VRCFaceTracking.

Make sure that you have **MeowFace**'s *IP* and *port* configured as specified by **VRCFaceTracking** and that you are connected to the same network as the host. Optionally you can send the data to the port to your global IP from any MeowFace connection by port forwarding the specified port.

> MeowFace is not tracking as expected.

MeowFace is not all too perfect at tracking your face... however: some of the tracking may not track as expected when converted for use into VRCFaceTracking's parameter system. Feel free to make an issue if MeowFace doesn't track as expected!
  
## Licenses / Distribution

**All source and release files fall under the [Apache-2.0 License](https://github.com/regzo2/VRCFaceTracking-Modules/blob/master/LICENSE.txt)**.

## Credits
- [Ben](https://github.com/benaclejames/) for VRCFaceTracking!
