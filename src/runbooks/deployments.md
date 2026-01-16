# Deployments

## Process
- Deploy to staging on branch `dev`
- Create merge request to `main`
- CI runs automatically
- Runs linting checks
- Runs playwright tests
- TBD: Runs Vitest
- Checks for successful staging deployment 
- Deployment monitored through HoneyBadger (needs to be updated)

## Rollbacks
- Prefer revert over hotfix