cmake_minimum_required(VERSION 2.8.3)
project(yolov3_detector)

find_package(catkin)

catkin_package()
catkin_python_setup()

catkin_package(
  LIBRARIES yolov3_detector
)

install(
  PROGRAMS
    
  DESTINATION
    ${CATKIN_PACKAGE_BIN_DESTINATION}
)
