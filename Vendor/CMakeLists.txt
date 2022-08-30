include(ExternalProject)

include(json.cmake)
include(websocketpp.cmake)
include(filesystem.cmake)

# TODO: remove on other platforms too when they have adequate std::format support
if (NOT MSVC)
  include(fmt.cmake)
endif ()
