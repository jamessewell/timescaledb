# Add all *.c to sources in upperlevel directory
set(SOURCES
  ${CMAKE_CURRENT_SOURCE_DIR}/uuid.c
  ${CMAKE_CURRENT_SOURCE_DIR}/metadata.c
  ${CMAKE_CURRENT_SOURCE_DIR}/telemetry.c
)
target_sources(${PROJECT_NAME} PRIVATE ${SOURCES})
