# Event-Driven AAP Workshop — exercise materials

Rulebooks, Job Template playbooks, Floci helpers, and student scripts for the
Zero-Touch lab **Event-Driven Ansible: From Event to Verified Outcome**.

## Layout

- `rulebooks/` — starter and final-example rulebooks learners grow across modules
- `playbooks/` — seed / remediate / verify / reset playbooks for Floci tracks
- `roles/floci_seed/` — shared seed tasks
- `bin/` — `inject-alert.sh` and `reset-track.sh`

## Lab consumption

- Project Zero Gitea migrates this repository into the student Gitea instance
- `setup-automation` clones this repository onto the control VM under
  `/usr/local/share/eda-lab/` and `~/eda-lab/materials/`

Point AWS modules at Floci with `endpoint_url` (default
`https://floci-$GUID.$DOMAIN`, or set `FLOCI_ENDPOINT`).
