cmake_minimum_required(VERSION 3.0.0)
# file(COPY ${CMAKE_CURRENT_SOURCE_DIR}/test.txt
#      DESTINATION ${CMAKE_CURRENT_BINARY_DIR})
set(PROJECT_NAME project1)
project(project1 VERSION 0.1.0)
add_executable(project1 main.cpp)
# add_executable(project1 Actor.cpp)
# 这是时刻更新的语句
# configure_file(input.txt input.txt COPYONLY)

# 这是只复制一次的选项，可以用来拷贝dll等关键文件
# add_custom_command(
#   TARGET ${PROJECT_NAME} POST_BUILD
#   COMMAND ${CMAKE_COMMAND} -E copy
#     ${CMAKE_CURRENT_SOURCE_DIR}/input.txt 
#     $<TARGET_FILE_DIR:${PROJECT_NAME}>)

# aux_source_directory(. SRC)
#aux_source_directory(. SRC)
#add_executable(project1 ${SRC})
#这里是将当前目录加入到编译中
#这里是头文件包括的目录
#include_directories(${PROJECT_SOURCE_DIR}/include)
#这里是头文件的实现，进行链接
#add_subdirectory(src)
# add_executable(project1 ${SRC})
#target_link_libraries(project1 source)
#这是启动debug模式的参数
#set(CMAKE_CXX_FLAGS  "${CMAKE_CXX_FLAGS} -g")
