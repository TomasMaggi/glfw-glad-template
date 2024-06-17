# CMakeList.txt: proyecto de CMake para openglTemplate, incluya el origen y defina
# la lógica específica del proyecto aquí.
#

# Agregue un origen al ejecutable de este proyecto.
add_executable (openglTemplate "main.cpp"  )

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET openglTemplate PROPERTY CXX_STANDARD 20)
endif()

# TODO: Agregue pruebas y destinos de instalación si es necesario.
