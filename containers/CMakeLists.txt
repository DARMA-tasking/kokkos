

KOKKOS_SUBPACKAGE(Containers)

IF (NOT Kokkos_INSTALL_TESTING)
  ADD_SUBDIRECTORY(src)
ENDIF()

KOKKOS_ADD_TEST_DIRECTORIES(unit_tests)
KOKKOS_ADD_TEST_DIRECTORIES(performance_tests)

KOKKOS_SUBPACKAGE_POSTPROCESS()
