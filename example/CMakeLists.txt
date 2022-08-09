#
# Copyright Soramitsu Co., Ltd. All Rights Reserved.
# SPDX-License-Identifier: Apache-2.0
#

include_directories(${WORKSPACE_ROOT_DIR}/deps/GSL-2.0.0/include)

add_subdirectory(01-echo)
add_subdirectory(02-kademlia)
add_subdirectory(03-gossip)
add_subdirectory(04-dnstxt)
add_subdirectory(SimpleEthClient)
