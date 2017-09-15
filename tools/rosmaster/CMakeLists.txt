cmake_minimum_required(VERSION 2.8.3)
project(rosmaster)
find_package(catkin REQUIRED)
catkin_package()

catkin_python_setup()

#if(CATKIN_ENABLE_TESTING)
if(0)
  catkin_add_nosetests(test)
endif()
