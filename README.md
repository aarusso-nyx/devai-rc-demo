# DEVAI installed-package adopter proof

This repository records installed-package adopter walkthroughs against exact package tarballs
assembled by DEVAI's non-publishing release rehearsals. The original fresh-repository proof used
rc.5; the same repository was then rebound and exercised end to end with the final rc.6 candidate.

- Source tag: `v1.0.0-rc.6`
- Source commit: `82bae11a0b01c15c5ddd15e5589ccdd0797f905d`
- Source tree: `d2d92eae1f27890faba82a1b22d96985f5b14c0f`
- Workflow run: `31554800131`
- Package SHA-256: `dab17b6c6cce6450a24d6daaa0c37adc30bb79bc3da9a0467698ef62c2f07959`

The package was installed with `npm install --no-save <tarball>`. The committed `evidence/`
directory contains structured results for both the fresh rc.5 adoption and the rc.6 rebind and
upgrade. Generated DEVAI bindings and both Codex and Claude recipe installations are committed as
observable adopter state.

The package is not yet published. Reproduction currently requires the authenticated rehearsal
artifact from the linked DEVAI workflow run.

## Result

The combined walkthrough passed unbound discovery, structured doctor review, all binding and apply
segments, Codex and Claude recipe installation and repeat idempotency, packaged-policy checks, the
missing adopter-DAG diagnostic, project-local hook installation, conflict preflight rollback, the
actual pre-push hook, and the documented removal procedure. The rc.6 pass also proves installed
package replacement, bundled-contract rebinding, exact version persistence, hook replacement, and
idempotent harness reapplication. Post-adoption doctor remains `review` because this deliberately
empty fixture does not invent adopter-owned product, law, or documentation content.

The release workflow independently runs its installed-binary smoke from an empty Git repository;
run `31554800131` passed that smoke and skipped every publishing/deployment job.
