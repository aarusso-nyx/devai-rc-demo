# DEVAI installed-package adopter proof

This repository records installed-package adopter walkthroughs against exact package tarballs
assembled by DEVAI's non-publishing release rehearsals. The original fresh-repository proof used
rc.5; the same repository was rebound for rc.6 and has now been upgraded to the exact stable 1.0
candidate on merged `main`.

- Source tag: `v1.0.0` (signed local rehearsal only; not pushed)
- Source commit: `c63698e7fd5f01c48fca28893f36ac6c73b7c80c`
- Source tree: `20d13995bf1bd469ab761893f894ccc534a24165`
- Exact-main ledger run: `31567312426`
- Package SHA-256: `6634e5151873abb0e617fa303c9a4476f856b5754b02a7cb6bbc97911334c0f3`

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
