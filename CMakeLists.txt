rcmake_minimum_required(VERSION 3.10)

# set the project name
project(MultiView)

# add the executable
add_executable(Server.cxx)

add_executable(${PROJECT_NAME} ${SOURCE_FILES} ${HEADER_FILES} ${SHADER_FILES})
