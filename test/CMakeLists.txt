cmake_minimum_required(VERSION 2.8)

find_package(UnitTest++ REQUIRED)
include_directories(${UNITTEST++_INCLUDE_DIR})

add_executable(unittests
	main.cpp
)
target_link_libraries(unittests
	${UNITTEST++_LIBRARY}
)

