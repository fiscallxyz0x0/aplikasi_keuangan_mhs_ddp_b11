cmake_minimum_required(VERSION 3.15)
project(TUGAS_BESAR_DDP_S1 C)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)

# Export compile_commands.json
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

# Include path
include_directories(${PROJECT_SOURCE_DIR}/include)

# Source files
file(GLOB SRC_FILES ${PROJECT_SOURCE_DIR}/src/*.c)

# Executable
add_executable(aplikasi_keuangan_mhs_ddp_b11 ${SRC_FILES})
