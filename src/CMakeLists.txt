cmake_minimum_required(VERSION 3.28.3)

project(CPP_Experiments)
# This command defines the name of the project. 
# It is used to initialize several variables that are used by CMake, 
# such as ${PROJECT_NAME}. 
# In this case, the project is named "CPP_Experiments".

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 17)  # 11 or 14, 17, etc.
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(${PROJECT_NAME} main.cpp)
# This command adds an executable target to the project. 
# It creates an executable file with the name specified by ${PROJECT_NAME} 
# (which is "CPP_Experiments" in this case) 
# and includes the source file main.cpp. 
# The main.cpp file is assumed to contain the entry point (main function) 
# of the program.