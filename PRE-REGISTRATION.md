# Pre-registration

**Committed 2026-07-27 — before the first public-records request was sent.**

The methodology for this study was written and finalized before any data existed. Rather than ask
you to take that on trust, its cryptographic hash is published here now. The full text publishes
with the first results.

## The commitment

| | |
|---|---|
| **File** | `methodology.md` |
| **SHA-256** | `1A869178CC98DAE027C2A84E08E8E1ECD62BACEFA1DFCE11E3944A4DF6DEF1E2` |
| **Size** | 10,891 bytes |
| **Fixed** | 2026-07-27 |
| **Requests dispatched** | 2026-07-28 |
| **Full text publishes** | 2026-08-17 |

## Why publish a hash instead of the document

Two things are in tension. A study like this is only credible if the standard was set before anyone
knew who it would favor — which argues for publishing the methodology immediately. But the requests
are deliberately not identified as part of a study, because an agency that knows it is being scored
does not behave the way it behaves on a normal Tuesday, and the normal Tuesday is the subject.

Publishing the hash resolves both. The document is locked today and cannot be altered without
detection; nothing about the study is revealed to the agencies being measured.

## How to verify, on 2026-08-17 or any time after

When `methodology.md` is published here, hash it yourself:

```
sha256sum methodology.md
```
```powershell
Get-FileHash methodology.md -Algorithm SHA256
```

If the result matches the value above — recorded in this repository's git history on 2026-07-27,
before the requests went out — then the methodology you are reading is the one that was written
before the data existed. If it does not match, the methodology changed after results started
arriving, and you should treat the findings accordingly.

**That is the point. You should not have to trust me.**

## What is deliberately not committed here

The target list is frozen but not published in advance, for the same reason the requests are not
identified. It publishes in full with the results, and the freeze date is verifiable in the same way.
No agency was added or removed after 2026-07-28.
