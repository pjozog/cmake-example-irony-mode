add_library(hello_irony_lib my_class.cc my_class.h)
add_executable(hello_irony main.cc)
target_link_libraries(hello_irony hello_irony_lib)
