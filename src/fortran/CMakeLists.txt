add_executable(stokes_ale_fortran stokes_ale.F90)

target_link_libraries(stokes_ale_fortran PRIVATE opencmisslibs mpi)

install(TARGETS stokes_ale_fortran DESTINATION bin)
