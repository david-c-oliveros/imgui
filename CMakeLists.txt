add_library(imgui imgui.cpp
                  imgui_widgets.cpp
                  imgui_draw.cpp
                  imgui_tables.cpp
                  imgui_demo.cpp
                  backends/imgui_impl_opengl3.cpp
                  backends/imgui_impl_glfw.cpp
                  )   

target_include_directories(${PROJECT_NAME}
    PUBLIC ../)
