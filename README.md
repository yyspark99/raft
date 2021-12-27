# raft
the raft consensus

# how to use
1 checkout the code, and copy sk_memory_node into raft's examples folder.

2 append the following to raft-rs's Cargo.toml.

[[example]]

name = "sk_mem_node"

path = "examples/sk_mem_node/main.rs"

3 build & run
