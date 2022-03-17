add_executable(Demo
    main.cu
)
add_dependencies(Demo cuNSearch)
target_link_libraries(Demo PRIVATE cuNSearch)


add_executable(Demo_luciano
    main_luciano.cu
)
add_dependencies(Demo_luciano cuNSearch)
target_link_libraries(Demo_luciano PRIVATE cuNSearch)
