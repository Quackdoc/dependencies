project(exrtest LANGUAGES CXX)

find_package(OpenEXR CONFIG REQUIRED)

add_executable(test main.cpp)

target_link_libraries(test PRIVATE OpenEXR::OpenEXR)
