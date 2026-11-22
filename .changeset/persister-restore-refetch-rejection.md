---
'@tanstack/query-persist-client-core': patch
---

Fix `experimental_createQueryPersister` causing an unhandled promise rejection when the background refetch after restoring a stale query fails.
