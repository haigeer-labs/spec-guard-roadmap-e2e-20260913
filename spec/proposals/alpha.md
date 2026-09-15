# Proposal: Add alpha acceptance module
<!-- spec-guard-proposal:v1 id=alpha -->

## Summary

Add the independently reviewable alpha module used to prove that a human-merged
Proposal can become the remote-default baseline for the next module.

## Capability map baseline

| Field | Value |
| --- | --- |
| Remote | origin |
| Default branch | main |
| Commit | 668080d5e8efcf54d8b26a601aa5c3f8e0447d08 |
| Capability map | spec/CAPABILITY-MAP.md |
| Goal digest | 20b5c43687de |
| Build order | foundation |

### Module digests

| Module id | Row digest |
| --- | --- |
| foundation | 3d5a064ad017 |

## Change

| Field | Value |
| --- | --- |
| Type | new-module |
| Module id | alpha |
| Responsibility | Prove the reviewed alpha module can be promoted from remote main. |
| Depends on | foundation |
| Build-order anchor | after:foundation |

## Tracker contract

| Field | Value |
| --- | --- |
| Proposal id | alpha |
| Identity label | proposal |
| Stage label namespace | proposal-stage: |
