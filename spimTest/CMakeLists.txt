project(spimTest)

cmake_minimum_required(VERSION 3.10)

set(INC_DIR /usr/local/include)

set(LINK_DIR /usr/local/lib)

include_directories(${INC_DIR}) 
link_directories(${LINK_DIR})


add_executable(spimTest src/spimTest.c)
target_link_libraries(spimTest libft4222.so)