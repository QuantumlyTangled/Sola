﻿project(NeskoncniPoskusGesla)

set(NESKONCNI_POSKUS_GESLA_HEADERS
)
set(NESKONCNI_POSKUS_GESLA_SOURCES
)

set(NESKONCNI_POSKUS_GESLA_EXECUTABLE_HEADERS
  ${NESKONCNI_POSKUS_GESLA_HEADERS}
)
set(NESKONCNI_POSKUS_GESLA_EXECUTABLE_SOURCES
  ${NESKONCNI_POSKUS_GESLA_SOURCES}
  src/main.cpp
)

add_executable(NeskoncniPoskusGesla ${NESKONCNI_POSKUS_GESLA_EXECUTABLE_HEADERS} ${NESKONCNI_POSKUS_GESLA_EXECUTABLE_SOURCES})
