cmake_minimum_required(VERSION 2.8)
project( camera_calibration )
find_package( OpenCV REQUIRED )
add_executable( camera_calibration camera_calibration.cpp )
target_link_libraries( camera_calibration ${OpenCV_LIBS} )
