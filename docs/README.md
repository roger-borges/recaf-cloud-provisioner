# Recaf Cloud Provisioner

You can use the Recaf Cloud Provisioner to supplement your AWS configuration experience. This repository is used to manage the releases, which are free to use.

There is only one feature available in this super early release:

- IAM RunAs
-- All of the features here revolve around easing the complicated nature that AWS's Assume Role functionality sometimes has.
-- Create a temporary Admin User
-- Give another account access to your account
-- Give people in your account access to other accounts

## IAM RunAs

Use the IAM RunAs configuration to set yourself up to access other accounts from your account. This is especially useful if you are in an AWS Organization, or you are a contractor who routinely accesses client accounts using your own account.

## Releases

You can view the latest releases here: [Recaf Cloud Provisioner releases](https://github.com/roger-borges/recaf-cloud-provisioner/releases)

Mac and Windows are supported.

## Technical Details

This application is written in Electron with Angular 6, and about a million other libraries:

- Angular v7.0.0
- Electron v3.0.5
- Angular CLI v7.0.2
- Angular Material v7.0.1
- Angular Flex Layout v7 beta
- AWS-SDK v2.301.0