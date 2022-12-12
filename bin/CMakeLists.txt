# --- onewire-temperature-factory
ADD_EXECUTABLE(
  onewire-temperature-factory

  onewire-temperature-factory.cpp
  )

TARGET_LINK_LIBRARIES(
  onewire-temperature-factory

  sensors
  )

# --- sensors-avg
ADD_EXECUTABLE(
  sensors-avg

  sensors-avg.cpp
  )

TARGET_LINK_LIBRARIES(
  sensors-avg

  sensors
  )
