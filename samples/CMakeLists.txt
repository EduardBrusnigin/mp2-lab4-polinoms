set(SRC main_polinom.cpp)

include_directories(../include)


add_executable(main ${SRC})
target_link_libraries(main polynomials)
