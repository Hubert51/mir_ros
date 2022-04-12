# mir_ros

### basic dependency
* websocket
  * pip2 install websocket
  * pip2 install websocket-client

### dependency
* [robot_localization/ekf_localization](https://github.com/cra-ros-pkg/robot_localization)
  * [geographic_msgs](https://github.com/ros-geographic-info/geographic_info)
  * [uuid_msgs](https://github.com/ros-geographic-info/unique_identifier)
  * [geographiclib](https://github.com/ethz-asl/geographic_lib)
    * `sudo apt-get install libgeographic-dev`
  * [catkin_simple](https://github.com/catkin/catkin_simple)
* mir-naviagation
  * amcl: including in navigation repo 
    * probabilistic localization system for a robot moving in 2D
  * map_server
    * SDL REQUIRED: 
      * `sudo apt-get install libsdl-image1.2-dev`
      * `sudo apt-get install libsdl-dev`
  * move_base
    * sbpl: global planner used in move_base
      * `sudo apt-get install ros-distro-sbpl`
