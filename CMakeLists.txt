project(cura-slm)

cmake_minimum_required(VERSION 2.8.12)
include(GNUInstallDirs)

install(DIRECTORY cura/resources DESTINATION ${CMAKE_INSTALL_DATADIR}/cura)
install(DIRECTORY cura/plugins DESTINATION lib${LIB_SUFFIX}/cura)
