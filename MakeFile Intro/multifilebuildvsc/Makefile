CXX			:= g++
CXXFLAGS 	:= -std=c++11 -Wall -Wextra -Werror -g -I.

MSG_START	:= "Build Started"
MSG_END		:= "Build Complete"
MSG_CLEAN	:= "Cleaning up"

BUILD_DIR	:= ./bin
SRC_DIR		:= ./src

TARGET		:= ${BUILD_DIR}/sampleapp.bin

SRC			:= ${SRC_DIR}/main.cpp ${SRC_DIR}/sample_function.cpp

all			:= build

hello:
	echo "Checking that tabs are setup correctly"

build:
	@echo "Build Started"
	g++ -o sampleapp ./src/main.cpp ./src/sample_function.cpp -I.
	@echo "Build Complete"
	./sampleapp


clean:
	@echo "Cleaning up"
	rm *.o