# onewire-temperature-factory
# ---------------------------

# ???

# sensors-avg
# -----------

ADD_EXECUTABLE(
  sensors-avg

  sensors-avg.cpp
  )

TARGET_LINK_LIBRARIES(
  sensors-avg

  sensors
  )



ADD_EXECUTABLE(
  onewire-temperature-monolithic

  onewire-temperature-monolithic.cpp
  )

TARGET_LINK_LIBRARIES(
  onewire-temperature-monolithic

  sensors
  )



ADD_EXECUTABLE(
  onewire-temperature-oo

  onewire-temperature-oo.cpp
  )

TARGET_LINK_LIBRARIES(
  onewire-temperature-oo

  sensors
  )
