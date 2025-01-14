#
# Copyright Soramitsu Co., Ltd. All Rights Reserved.
# SPDX-License-Identifier: Apache-2.0
#

add_executable(libp2p_echo_server
    libp2p_echo_server.cpp
    )

target_include_directories(libp2p_echo_server PRIVATE ${WORKSPACE_ROOT_DIR}/deps/di-1.1.0/include)
target_include_directories(libp2p_echo_server PRIVATE ${WORKSPACE_ROOT_DIR}/deps/soralog-0.0.9/include)
target_include_directories(libp2p_echo_server PRIVATE ${WORKSPACE_ROOT_DIR}/deps/yaml-cpp-yaml-cpp-0.6.2/include)

target_link_libraries(libp2p_echo_server
    p2p_basic_host
    p2p_default_network
    p2p_peer_repository
    p2p_inmem_address_repository
    p2p_inmem_key_repository
    p2p_inmem_protocol_repository
    p2p_protocol_echo
    p2p_literals
    )

add_executable(libp2p_echo_client
    libp2p_echo_client.cpp
    )

target_include_directories(libp2p_echo_client PRIVATE ${WORKSPACE_ROOT_DIR}/deps/di-1.1.0/include)
target_include_directories(libp2p_echo_client PRIVATE ${WORKSPACE_ROOT_DIR}/deps/soralog-0.0.9/include)
target_include_directories(libp2p_echo_client PRIVATE ${WORKSPACE_ROOT_DIR}/deps/yaml-cpp-yaml-cpp-0.6.2/include)

target_link_libraries(libp2p_echo_client
    p2p_basic_host
    p2p_default_network
    p2p_peer_repository
    p2p_inmem_address_repository
    p2p_inmem_key_repository
    p2p_inmem_protocol_repository
    p2p_protocol_echo
    p2p_literals
    )
