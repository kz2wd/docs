---
outline: deep
title: Maintainer PR Guide
---

# Maintainer PR Guide

::: info

This information is mostly relevant to the team members of Mockbukkit.
We nevertheless provide this information publicly as to encourage transparency
and attract new people to help drive this project forward!

:::

We use [Github Labels](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels)
to automatically tag PRs with a version number on merge. This removes the tedious work of keeping version numbers up
to date across several PRs at a time and eliminate Human error. The following custom labels, all of them following the
pattern of `release/*`, are used by Mockbukkit:

| Label                                        | Semantic Version Type |   | Description                            |
|----------------------------------------------|:----------------------|:--|:---------------------------------------|
| <Badge type="danger" text="release/major"/>  | Major Version (X.0.0) |   | Only used for breaking changes         |
| <Badge type="warning" text="release/minor"/> | Minor Version (0.X.0) |   | New Features                           |
| <Badge type="tip" text="release/patch"/>     | Patch Version (0.0.X) |   | Bug Fixes                              |
| <Badge type="info" text="release/none"/>     | None (-)              |   | Method Stubs or non code related fixes |

As you can probably tell, this project uses [Semantic Versioning](https://semver.org/).