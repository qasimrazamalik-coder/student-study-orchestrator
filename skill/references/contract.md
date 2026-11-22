# Contract

## Capability
Build spaced, workload-bounded study plans from topics, deadlines, confidence and available sessions.

## Input root
`items` with fields: id, priority, effort, channel.

## Output
JSON containing `skill` and deterministic findings, ranking, mapping, plan or redaction results.

Reject malformed JSON. Do not infer authorization or fabricate evidence.
