project(xp-test)

add_library(${PROJECT_NAME}
    src/main.cpp
)

target_include_directories(${PROJECT_NAME} PUBLIC external)
