add_executable(stokes_ale_fortran burgers_static.F90)

target_link_libraries(burgers_static_fortran PRIVATE opencmisslibs mpi)

install(TARGETS burgers_static_fortran DESTINATION bin)
