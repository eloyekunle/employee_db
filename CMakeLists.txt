cmake_minimum_required(VERSION 3.6)
project(Employee)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
    Database.cpp
    Database.h
#    DatabaseTest.cpp
    Employee.cpp
    Employee.h
#    EmployeeTest.cpp
    UserInterface.cpp)

add_executable(Employee ${SOURCE_FILES})