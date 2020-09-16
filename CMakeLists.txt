cmake_minimum_required(VERSION 3.17)

project(imgui)
add_definitions(-DIMGUI_API=__declspec\(dllimport\))
add_library(imgui imconfig.h imgui.h imgui.cpp imgui_draw.cpp imgui_internal.h imgui_widgets.cpp imstb_rectpack.h imstb_textedit.h imstb_truetype.h imgui_demo.cpp)
