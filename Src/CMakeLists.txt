add_executable(${PROJECT_NAME} 
    Main.cpp
)

target_link_libraries(${PROJECT_NAME} PUBLIC 
    fmt 
    ${CMAKE_THREAD_LIBS_INIT}
)

target_include_directories(${PROJECT_NAME} PUBLIC .)