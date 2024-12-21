

# add_subdirectory(common)

add_subdirectory(pybind11)
pybind11_add_module(example main.cpp)