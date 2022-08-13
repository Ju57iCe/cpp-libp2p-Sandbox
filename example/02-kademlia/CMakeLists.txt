#
# Copyright Soramitsu Co., Ltd. All Rights Reserved.
# SPDX-License-Identifier: Apache-2.0
#

add_executable(rendezvous_chat
rendezvous_chat.cpp
)

target_include_directories(rendezvous_chat PRIVATE ${WORKSPACE_ROOT_DIR}/deps/di-1.1.0/include)
target_include_directories(rendezvous_chat PRIVATE ${WORKSPACE_ROOT_DIR}/deps/soralog-0.0.9/include)
target_include_directories(rendezvous_chat PRIVATE ${WORKSPACE_ROOT_DIR}/deps/yaml-cpp-yaml-cpp-0.6.2/include)

target_link_libraries(rendezvous_chat
    p2p_basic_host
    p2p_default_network
    p2p_peer_repository
    p2p_inmem_address_repository
    p2p_inmem_key_repository
    p2p_inmem_protocol_repository
    p2p_literals
    p2p_kademlia
    asio_scheduler
    p2p_multiaddress
    )
