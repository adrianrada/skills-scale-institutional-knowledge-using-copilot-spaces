# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (verified by DevOps Engineer)
- Release notes drafted (Technical Writer with input from Product Manager)
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared (QA Lead)
- Final QA sign-off (QA Lead)
- Stakeholder approval for release (if required)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — Project Manager coordinates
- [ ] Backup or snapshot (if applicable) — DevOps Engineer
- [ ] Deploy to staging and run smoke tests — QA Lead verifies
- [ ] Deploy to production (automated pipeline preferred) — DevOps Engineer executes
- [ ] Run post-deploy verifications — QA Lead and DevOps Engineer
- [ ] Announce release to stakeholders and support — Product Manager and Technical Writer
- [ ] Update documentation — Technical Writer

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer leads)
  - Rollback to last known-good release if necessary (DevOps Engineer executes)
  - Triage root cause and capture action items (Project Manager coordinates with team)
  - Communicate status to Stakeholders and Sponsor (Project Manager and Product Manager)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
