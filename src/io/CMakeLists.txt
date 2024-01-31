target_sources(${PROJECT_NAME}_lib PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}/fileloader.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/filestream.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/io_wheel.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/iobestiary.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/io_bosstiary.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/ioguild.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/iologindata.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/functions/iologindata_load_player.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/functions/iologindata_save_player.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/iomap.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/iomapserialize.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/iomarket.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/ioprey.cpp
)
