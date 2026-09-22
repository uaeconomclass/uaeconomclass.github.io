# History maintenance

On 2026-09-23, the local `main` history was redistributed evenly across
2021-09-23 through 2026-09-23 at the repository owner's request. Author and
committer dates were both rewritten; these dates are a chosen schedule, not
the original development dates. Commit order, messages, and file contents
were preserved, except for removal of LLM co-author trailers requested by
the owner, with this maintenance note added before redistribution. Commit
signatures were removed because rewriting invalidates them.

The original refs are saved in a Git bundle under the local Git directory,
named `history-before-redistribution-<timestamp>.bundle`. Existing backup tags
tags are unchanged. The owner also authorized publishing the rewritten
`main`; use `--force-with-lease` to protect against unexpected remote changes.
