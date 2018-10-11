# Recaf Cloud Provisioner

You can use the Recaf Cloud Provisioner to supplement your AWS configuration experience. This repository is used to manage the releases, which are free to use.

There is only one feature available in this super early release:

- IAM RunAs

## IAM RunAs

Use the IAM RunAs configuration to set yourself up to access other accounts from your account. This is especially useful if you are in an AWS Organization, or you are a contractor who routinely accesses client accounts using your own account.

## Releases

You can view the latest releases here: [Recaf Cloud Provisioner releases](https://github.com/roger-borges/recaf-cloud-provisioner/releases)

Mac and Windows are supported.

## Technical Details

This application is written in Electron with Angular 6, and about a million other libraries:

- Angular v6.1.2
- Electron v2.0.7
- Electron Builder v20.28.1
- Angular CLI
- Angular Material
- Angular FlexBox
- AWS-SDK