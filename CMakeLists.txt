PROJECT(ZeroSim)

# Indicamos la versión mínima que necesitamos de CMake
CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

# Creamos la variable MiProyecto_SRC y le asignamos el valor "src/main.cpp" que es la ubicación de nuestro archivo.
SET(ZeroSim "src/Main.cpp")

# Se creará un ejecutable llamado MiProyecto en Linux o MiProyecto.exe en Windows.
# Se hace referencia a las variables con ${NOMBRE_VARIABLE}.
ADD_EXECUTABLE(ZeroSim ${ZeroSim})
