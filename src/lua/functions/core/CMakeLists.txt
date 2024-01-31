target_sources(${PROJECT_NAME}_lib PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}/game/config_functions.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/game/game_functions.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/game/bank_functions.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/game/global_functions.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/game/lua_enums.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/game/modal_window_functions.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/game/zone_functions.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/libs/bit_functions.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/libs/db_functions.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/libs/result_functions.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/libs/logger_functions.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/libs/metrics_functions.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/libs/kv_functions.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/network/network_message_functions.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/network/webhook_functions.cpp
)
