cmake_minimum_required(VERSION 2.4.6)
project(raw_description)

find_package(catkin REQUIRED COMPONENTS)

#catkin_package(CATKIN_DEPENDS xacro)
catkin_package(CATKIN_DEPENDS)

install(DIRECTORY urdf
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

install(DIRECTORY Media
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

install(DIRECTORY meshes
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
