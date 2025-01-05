• Implemented a replicated distributed service using a primary-backup protocol, leveraging state machine replication to maintain consistency across multiple nodes.
• Built multi-threaded servers and clients that share key-value store while handling node failures.
• Implemented a server recovery mechanism where failed servers are repaired by restarting them with the same configurations while ensuring data consistency by synchronizing repaired servers with live servers before rejoining them.
