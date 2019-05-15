cmake_minimum_required(VERSION 2.8.3)
project(ros_opencv_pylon)

find_package(catkin REQUIRED COMPONENTS
 roscpp

 std_msgs
 cv_bridge
 sensor_msgs
 image_transport
)
find_package(OpenCV REQUIRED)
# target_link_libraries(ros_opencv_pylon ${OpenCV_LIBRARIES})
