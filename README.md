# Intelligent Pipelines: Bringing AI/ML into DevSecOps Automation

This project explores bringing AI/ML into DevSecOps automation with Tekton:
pipelines that do more than run fixed steps in order — they use intelligent,
data-driven decisions to make software delivery faster, safer, and more
reliable.

## The idea

Traditional CI/CD pipelines execute the same stages every time, regardless of
context. An intelligent pipeline adapts: it can prioritize what to test based
on what changed, surface the most relevant signals from build and deployment
data, and help teams catch problems earlier — while keeping humans in control
of every release decision.

## Current status

This repository is the starting point for the project: it currently holds
this overview only, and no pipeline definitions yet. The companion
application-side repository is
[`intelligent-tekton-pipeline-app`](https://github.com/psehgaft/intelligent-tekton-pipeline-app).

## Planned directions

- Tekton pipeline definitions that embed AI/ML-assisted steps alongside
  standard build, test, and deploy stages.
- Using pipeline and delivery data to prioritize testing and highlight risk
  before a change ships.
- Clear, auditable pipeline runs: every automated recommendation traceable to
  the data and step that produced it.

These directions describe the project's goals, not shipped functionality —
contributions that turn any of them into working pipelines are welcome.

## Usage

There is nothing to install or run from this repository yet. Watch this space
for pipeline definitions, and see the companion application repository for
the application side of the project.

## License

This repository is licensed under the GNU General Public License v2.0 —
see `LICENSE` for details.
