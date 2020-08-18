# 3d-mapping-on-budget
3d-mapping-on-budget [draft]

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

Binaries available for Linux, Mac, Windows, Raspberry Pi, Docker

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

# Stereo cameras

Many models available. 

# RGB-D cameras

Only a few (older) models available

# LIDAR

Low budget LIDAR scanners are 2D scanners. 3D scanners are also available much cheaper than some years ago, but all available scanners are not ready to use for production mapping and require some setup, API calls...

https://github.com/introlab/rtabmap/issues/390

| Type   | Model            | Detail                                   | Price  | Available |
| ------ | ---------------- | ---------------------------------------- | ------ | --------- |
|   2D   | Aikeek           | Aikeek HLS-LFCD2                         |   45   |  YES      |
|   2D   | YDLIDAR X4       |                                          |   90   |  YES      |
|   2D   | YDLIDAR X2L      |                                          |   90   |  YES      |
|   2D   | RPLIDAR A1       | Lidar A1M8                               |   100  |  YES      |
|   2D   | YDLIDAR TX8 TOF  |                                          |   135  |  YES      |
|   2D   | RPLIDAR          | Lidar A1M8                               |   130  |  YES      |
|   2D   | YDLIDAR G2       |                                          |   200  |  YES      |
|   2D   | NaviPack         |                                          |   300  |  YES      |
|   2D   | RPLIDAR A1       | Lidar A2M7                               |   320  |  YES      |
|   2D   | YDLIDAR TOF T15  |                                          |   1500 |  YES      |

Some of the low cost models don´t come with a usb connector




