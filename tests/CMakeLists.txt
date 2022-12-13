ADD_EXECUTABLE(
  FH-ECE20-final--suite

  fixture-tmpdir.h
  fixture-tmpdir.cpp

  sensor-const-suite-basic.cpp
  sensor-const-suite-is-a-sensor.cpp
  sensor-random-suite-basic.cpp
  sensor-random-suite-is-a-sensor.cpp

  sensor-w1-suite.cpp

  # ???
  )

TARGET_LINK_LIBRARIES(
  FH-ECE20-final--suite

  sensors

  gtest_main 
  )
