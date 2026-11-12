# GT-0221 hard negative: artifact name mismatch

The producer uploads `agent-result`, while the consumer downloads
`reviewed-result-v2`. The two channels do not establish a data handoff even
though both workflows and both actions are otherwise reachable.
