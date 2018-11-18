cmake_minimum_required(VERSION 3.5)
project(integrate_tsukuba_challenge_2018)
find_package(catkin REQUIRED)
catkin_metapackage()
install(DIRECTORY launch/
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch)
