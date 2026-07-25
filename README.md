# official-lists-mirror

Rolling, bit-identical mirrors of **official, public** sanctions data for
build environments whose network position cannot reach the origin hosts.

Currently mirrored:

| Dataset | Origin | Rolling release |
| --- | --- | --- |
| UK Sanctions List (XML) | https://sanctionslist.fcdo.gov.uk/docs/UK-Sanctions-List.xml | [`uk-sanctions-list`](../../releases/tag/uk-sanctions-list) |

Each release carries the unmodified origin file plus `manifest.json` with the
origin URL, fetch timestamp, byte size, SHA-256 and record count. The public
Actions run logs are the audit trail; consumers must re-verify structure and
hashes on their side (the Modus pipeline does).

This repository contains no proprietary code or data — only officially
published public documents.
