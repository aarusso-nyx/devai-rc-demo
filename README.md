# DEVAI installed-package adopter proof

This repository records a fresh-repository adopter walkthrough against the exact package tarball
assembled by DEVAI's non-publishing `v1.0.0-rc.5` rehearsal.

- Source tag: `v1.0.0-rc.5`
- Source commit: `12406084a512a15eb6154d834038e628a51ff967`
- Workflow run: `31554217534`
- Package SHA-256: `c311d4a2e2ed111e0aea6d1f0755c0735035f4986ad39c07840c6ad0e64e21b1`

The package was installed into this fresh Git repository with `npm install --no-save <tarball>`.
The committed `evidence/` directory contains structured command results; generated DEVAI bindings
and both Codex and Claude recipe installations are committed as observable adopter state.

The package is not yet published. Reproduction currently requires the authenticated rehearsal
artifact from the linked DEVAI workflow run.

## Result

The walkthrough passed unbound discovery, structured doctor review, all binding and apply segments,
Codex and Claude recipe installation and repeat idempotency, packaged-policy checks, the missing
adopter-DAG diagnostic, project-local hook installation, conflict preflight rollback, the actual
pre-push hook on first publication, and the documented removal procedure. Post-adoption doctor
remains `review` because this deliberately empty fixture does not invent adopter-owned product, law,
or documentation content.
