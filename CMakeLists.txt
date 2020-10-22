cmake_minimum_required(VERSION 3.18)

project(LearnWxWidget VERSION 1.0)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

#set (CMAKE_CXX_FLAGS "-O0")

add_executable(${PROJECT_NAME} 
    src/main.cpp    
)

#link_directories(NaukaCMake ${CMAKE_SOURCE_DIR}/build/SpeedLight)
#target_link_libraries(NaukaCMake SpeedLight)

target_include_directories(LearnWxWidget PUBLIC 
    ${PROJECT_SOURCE_DIR}/include
)