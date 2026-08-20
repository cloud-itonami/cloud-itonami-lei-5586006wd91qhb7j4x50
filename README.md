# cloud-itonami-lei-5586006wd91qhb7j4x50

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by Saudi Arabian Oil Company.**

This repository archives the publicly published Terms of Service of **Saudi Arabian Oil Company** (SA), with source-url and retrieval-date provenance, per
ADR-2607110300 (`cloud-itonami-lei-corporate-tos-catalog`, `com-junkawasaki/root`).
Read-only reference/archive repository — not a governed Advisor/Governor actor.

- LEI: `5586006WD91QHB7J4X50` (GLEIF entity status ACTIVE, registration ISSUED)
- Source: https://www.aramco.com/en/terms-and-conditions
- Retrieved: 2026-07-25T05:18:42Z
- SHA-256 of archived text: `aa30ba2764f0164cc0e14fea70f79796112da5fb7198fca0a28d502a0ce3ad76`

Acquired by `scripts/lei-acquire.cljs` as part of the worldwide-broadening
continuation that followed the 2026-07-25 coverage audit, which found the
catalog's real reach was 27 countries with the United States at 55%.

## Verified registry facts

`facts.edn` records what GLEIF publishes about this LEI — the entity record, its
managing LOU and that LOU's accreditation, the Saudi commercial register that
corroborated it, its ISO 20275 legal form, both parent-reporting exceptions, a
count of its instrument identifiers and each of its 14 direct children — with
`:source/url` and `:source/retrieved-at` next to every value.

The 2,700 instrument identifiers are counted, not mirrored: at 180 pages they
turn over as instruments mature and are issued, which would keep this check red
for reasons that are not "the citation broke". The `:source/note` on that entity
says so, so a bare count is never ambiguous between "too many to mirror" and
"nobody looked".

Two recorded values are third-party websites GLEIF publishes (`:issuer/website`,
`:authority/website`), not sources this repository fetches. They are facts about
GLEIF's record and are checked against GLEIF like any other value; whether those
sites answer from any given network is a separate question and not one this
repository claims. The nine `:source/url` citations are all fetched on every run.

`nbb scripts/verify-facts.cljs` re-fetches those sources and compares. It exits
`0` when the live registry still agrees, `1` when a citation is dead or a value
drifted, and `3` when it could not check at all (sources unreachable, `facts.edn`
missing or unreadable) — a run that could not answer must not look like a pass.
`--write` regenerates the file through the same builder the check uses, so it
cannot drift from its own generator.
