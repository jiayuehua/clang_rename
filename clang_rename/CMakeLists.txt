# CMakeList.txt : CMake project for clang_rename, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

find_package(sqlite3 CONFIG REQUIRED)
# Add source to this project's executable.
add_executable (clang_rename "clang_rename.cpp" "clang_rename.h")


# TODO: Add tests and install targets if needed.
