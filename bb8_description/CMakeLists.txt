cmake_minimum_required(VERSION 2.8.3)
project(bb8_description)
find_package(catkin REQUIRED)

catkin_package(
  CATKIN_DEPENDS xacro
)

#############
## Install ##
#############

## Mark other files for installation (e.g. launch and bag files, etc.)
# install(FILES
#   # myfile1
#   # myfile2
#   DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
# )

