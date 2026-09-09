# Licensing note

This repository carries no `LICENSE` file, no `license` or `license-file` key
in `Cargo.toml`, and no repository-wide copyright headers. That is how it
arrives from upstream (`rustdesk/hbb_common`), not something this fork removed.

`hbb_common` is used by RustDesk as a submodule and workspace member of the
RustDesk source tree. In our builds and distributions, it is compiled into
RustDesk binaries and is not distributed by us as a standalone product.

The licence governing the RustDesk work as a whole is stated in the parent
repository:

* Upstream: https://github.com/rustdesk/rustdesk — AGPL-3.0, in `LICENCE`.
* Our fork: https://github.com/gesoft-admin/rustdesk — same licence, with
  `LICENCE-COMPLIANCE.md` documenting how we treat this repository's missing
  standalone licence declaration and what we do and do not claim about it.

This note exists for provenance and compliance documentation only. It does not
itself declare or assign a licence to upstream `hbb_common` code, nor should it
be read as a statement about the licence status of any historical
`hbb_common` revision.

Modifications authored by us are documented in the parent RustDesk fork and
made available with the corresponding source used for our RustDesk builds,
without purporting to relicense upstream material for which we do not hold
copyright.
