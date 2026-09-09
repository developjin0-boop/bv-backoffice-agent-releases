# BV Backoffice Agent — Releases

Installers for **BV Backoffice Agent**, the BV Loyalty agent that runs on a
merchant's head office server and writes members into `AcCustomer`.

Source lives in a private repository. This one exists only to host release
assets so the in-app updater can find them — each release carries the installer,
its blockmap, and `latest.yml`.

**This is not BV POS Agent.** That one runs on a till, writes to `AcCard`, and
has its own releases at [bv-pos-agent-releases](../../../bv-pos-agent-releases).
Both can be installed on the same machine; installing the wrong one is the
mistake this note exists to prevent.

Not for redistribution.
