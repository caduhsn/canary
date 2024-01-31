target_sources(${PROJECT_NAME}_lib PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}/di/soft_singleton.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/logging/log_with_spd_log.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/metrics/metrics.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/thread/thread_pool.cpp
)
