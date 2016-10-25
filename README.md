# AutoVR

A WebVR Boilerplate-based viewer for
sensor data from a ROS - based autonomous car.

## Start
    roscore
    rosbag play 2016-05-11-00-00-01.bag -l
    roslaunch rosbridge_server rosbridge_websocket.launch
    rosrun tf2_web_republisher tf2_web_republisher

Then configure (set serverUrl) and open index.html

## Thanks

- [Ricardo Cabello][doob] for THREE.js.
- [Boris Smus][smus] for webvr-boilerplate.


[doob]: https://twitter.com/mrdoob
[smus]: http://smus.com
