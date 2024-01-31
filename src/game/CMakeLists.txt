target_sources(${PROJECT_NAME}_lib PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}/functions/game_reload.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/game.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/bank/bank.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/movement/position.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/movement/teleport.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/scheduling/events_scheduler.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/scheduling/dispatcher.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/scheduling/task.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/scheduling/save_manager.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/zones/zone.cpp
)
