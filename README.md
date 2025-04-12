# This is a docker setting to user ROS2 on a raspberry pi.
### This was made for a robocup junior compitition - [Link to our github](https://github.com/NoamRon1/RoboCup_Gvanim_School/)

# Installation
### build the container
``` bash
docker build .
docker compose run my_ros2_container
```

# To get into the container
``` bash
docker exec -it my_ros2_container bash
```

# Credits
* [First ROS2 Program By Kevin McAleer](https://www.kevsrobots.com/learn/learn_ros/)
* Gal Arbel - [Github page](https://github.com/galarb)