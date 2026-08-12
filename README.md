# DEVAI installed-package adopter proof

This repository records installed-package adopter walkthroughs against exact package tarballs
assembled by DEVAI's non-publishing release rehearsals. The original fresh-repository proof used
rc.5; the same repository was rebound for rc.6 and has now been upgraded to the exact stable 1.0
candidate on merged `main`.

- Source tag: `v1.0.0` (not created or pushed)
- Source commit: `a9a16befc26a62f70fdce3c6acaf25086cd9735c`
- Source tree: `e2f7de0aaa88f460c4efaa44b16077d3f1b176a0`
- Exact-main ledger run: `31568790373`
- Package SHA-256: `b1662a1ca0b25e49a41333b057874221b936108c8d89fbb48740e35f3a1f9410`

The package was installed with `npm install --no-save <tarball>`. The committed `evidence/`
directory contains structured results for the fresh rc.5 adoption, the rc.6 rebind, and the stable
1.0 prepublication upgrade. Generated DEVAI bindings and both Codex and Claude recipe installations
are committed as observable adopter state.

The stable package is not yet published. Reproduction currently requires the locally assembled
tarball whose digest is recorded in `evidence/installed-package-v1.0.0-e2e.json`. The remote
non-publishing tag workflow remains pending until the signed `v1.0.0` tag is authorized and pushed.

## Result

The combined walkthrough passed unbound discovery, structured doctor review, all binding and apply
segments, Codex and Claude recipe installation and repeat idempotency, packaged-policy checks, the
missing adopter-DAG diagnostic, project-local hook installation, conflict preflight rollback, the
actual pre-push hook, and the documented removal procedure. The stable pass also proves installed
package replacement, bundled-contract rebinding, exact version persistence, hook replacement, and
idempotent harness reapplication. Post-adoption doctor remains a valid structured `review`: this
deliberately empty fixture does not invent adopter-owned product, law, or documentation content,
and it also reports the fixture's existing host-authority declaration mismatch.

The exact stable tarball independently passed the installed-binary smoke from an empty Git
repository. Remote tag-workflow rehearsal and every publishing/deployment job remain unrun.
