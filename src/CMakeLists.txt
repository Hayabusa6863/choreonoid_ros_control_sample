add_executable(sinewave_command sinewave_command.cpp)
add_dependencies(sinewave_command ${${PROJECT_NAME}_EXPORTED_TARGETS} ${catkin_EXPORTED_TARGETS})
target_link_libraries(sinewave_command ${catkin_LIBRARIES})