# CMakeList.txt: проект CMake для Lab_4_osiks; включите исходный код и определения,
# укажите здесь логику для конкретного проекта.
#

# Добавьте источник в исполняемый файл этого проекта.
add_executable (Lab_4_osiks "Lab_4_osiks.cpp" "Lab_4_osiks.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Lab_4_osiks PROPERTY CXX_STANDARD 20)
endif()

# TODO: Добавьте тесты и целевые объекты, если это необходимо.
