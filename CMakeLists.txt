cmake_minimum_required(VERSION 3.0.0)
project(day_to_day_expenses_app VERSION 0.1.0)

include(CTest)
enable_testing()

add_library(day_to_day_expenses_app day_to_day_expenses_app.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
