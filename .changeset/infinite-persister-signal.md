---
'@tanstack/query-core': patch
---

Fix infinite queries with a `persister` cancelling and discarding an in-flight fetch on unmount even when the `queryFn` never reads `signal`.
