cmake_minimum_required(VERSION 3.5)
project(Start
		VERSION 0.0.1
		DESCRIPTION "The loading Hello World App"
		LANGUAGES C)
add_executable(StartAppBinary start.c)
target_compile_features(StartAppBinary PRIVATE)