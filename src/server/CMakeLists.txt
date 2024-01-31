target_sources(${PROJECT_NAME}_lib PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}/network/connection/connection.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/network/message/networkmessage.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/network/message/outputmessage.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/network/protocol/protocol.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/network/protocol/protocolgame.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/network/protocol/protocollogin.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/network/protocol/protocolstatus.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/network/webhook/webhook.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/server.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/signals.cpp
)
