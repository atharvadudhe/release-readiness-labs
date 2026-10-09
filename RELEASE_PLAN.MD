# Release Documentation

This Documentations contains all the verifications and validations which have been done before going live.

So all the things are managed to go live for the production, the secrets, the versioing and all the files are confiered and tested, the approvals and the admins are also set, the release rollback has been set to 7 to insure we have enough changes.

## Deployment Check List

- Handled the hardcoaded secrets
- Handled the authors for the approvals 
- Define the rollback strategy
- Updated the workflow to make it run

## Release Versioninig

We are currently going live with the v2.3.0 and we have set rollback version to v1.9.4.

## Rollback

Set the rollback strategy to 7 and also defined the version v0.9 for the rollbacks.