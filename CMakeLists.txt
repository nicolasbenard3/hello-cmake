# CMakeList.txt : projet CMake pour hello Cmake, incluez la source et définissez
# la logique spécifique au projet ici.
#
cmake_minimum_required (VERSION 3.8)

project ("hello Cmake")

# Ajoutez une source à l'exécutable de ce projet.
add_executable (CMakeTarget "hello Cmake.cpp" "hello Cmake.h")

# TODO: Ajoutez des tests et installez des cibles si nécessaire.
