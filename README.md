# 3d-mapping-on-budget
3d-mapping-on-budget

Software and hardware for indoor and outdoor 3D-mapping

At the moment there are no ready-to-use 3d mapping solutions available for reasonable prices.

So far I did not find any handheld/portable 3D mapping devices that would be suitable for indoor and outdoor mapping.

If you are lucky and have ~8000$ you can buy a used terrestrial laser scanner that can store the scan without an additional computer.

New terrestrial laser scanners start at ~12000$

Of course there there is photogrammetry, but this is not optimal in all cases.

This is a try to collect open source software for 3D mapping and supported hardware.
The software setup should be easy.

Many popular and affordable RGB-D cameras are no longer available. 


# RTABmap

Real-Time Appearance-Based Mapping
http://wiki.ros.org/rtabmap

Binaries available for Linux, Mac, Windows

https://github.com/introlab/rtabmap/releases

RTABmap supports the following models. As you can see, most of them are no longer being sold.


| Type   | Model            | Driver                                   | Price  | Available |
| ------ | ---------------- | ---------------------------------------- | ------ | --------- |
| RGB-D  | Kinect           | Freenect, OpenNi2, OpenNi-PCL, OpenNi-CV | 250    | NO        |
| RGB-D  | Xtion PRO LIVE   | OpenNi2, OpenNi-PCL, OpenNi-CV-ASUS      | 200    | NO        |
| RGB-D  | Sense 3D scanner | OpenNi2                                  | 500    | YES       |
| RGB-D  | Kinect v2        | Freenect 2, Kinect for Windows SDK v2    | 380    | NO        |
| RGB-D  | Realsense R200   | Realsense                                | 200    | NO        |
| RGB-D  | Realsense ZR300  | Realsense                                | 70-400 | NO        |
| RGB-D  | Realsense D415   | Realsense 2                              | 180    | YES       |
| RGB-D  | Realsense D435   | Realsense 2                              | 217    | YES       |
| Stereo | Bumblebee2       | StereoDC1394, FlyCapture2                | 3500   | YES       |
| Stereo | Zed Camera       | Zed SDK                                  | 400    | YES       |
| Stereo | Zed Camera       | Stereo Camera                            | 400    | YES       |
| Stereo | Tara Camera      | Tara Stereo USB Camera                   | 150    | YES       |
| RGB    | RGB camera       | USB Camera                               |        |           |

