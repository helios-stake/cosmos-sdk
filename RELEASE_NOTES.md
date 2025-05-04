
# Cosmos SDK v0.53.0 Release Notes

💬 [**Release Discussion**](https://github.com/orgs/cosmos/discussions/58)

## 🚀 Highlights

Announcing Cosmos SDK v0.53

We are pleased to announce the release of Cosmos SDK v0.53! We’re excited to be delivering a new version of the Cosmos SDK that provides key features and updates while minimizing breaking changes so you can focus on what matters most: building.

Upgrading to this verison of the Cosmos SDK from any `v0.50.x` release will **require a coordinated chain upgrade**.

For more upgrade information, check out our [upgrading guide](https://github.com/cosmos/cosmos-sdk/blob/v0.53.0/UPGRADING.md)

## 📝 Changelog

Check out the [changelog](https://github.com/cosmos/cosmos-sdk/blob/v0.53.0/CHANGELOG.md) for an exhaustive list of changes, or [compare changes](https://github.com/cosmos/cosmos-sdk/compare/v0.50.12...v0.53.0) from the last release.
This patch release fixes [GHSA-x5vx-95h7-rv4p](https://github.com/cosmos/cosmos-sdk/security/advisories/GHSA-x5vx-95h7-rv4p).
It resolves a `x/group` module issue that can halt chain when handling a malicious proposal.
Only users of the `x/group` module are affected by this issue.

We recommended to upgrade to this patch release as soon as possible.
When upgrading from <= v0.50.11, please use a chain upgrade to ensure that 2/3 of the validator power upgrade to v0.50.12.

## 📝 Changelog

Check out the [changelog](https://github.com/cosmos/cosmos-sdk/blob/v0.50.12/CHANGELOG.md) for an exhaustive list of changes, or [compare changes](https://github.com/cosmos/cosmos-sdk/compare/v0.50.11...v0.50.12) from the last release.
