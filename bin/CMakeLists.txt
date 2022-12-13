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
