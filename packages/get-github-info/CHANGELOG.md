# @changesets/get-github-info

## 0.4.4

### Patch Changes

- [`f24f722`](https://github.com/atlassian/changesets/commit/f24f7220fcc322a4a2deb26cd77c2d481ac422f0) [#444](https://github.com/atlassian/changesets/pull/444) Thanks [@Andarist](https://github.com/Andarist)! - Changed the way how requests to the GitHub API were authenticated - from a query parameter to the `Authorization` header. The previously used method has been deprecated by the GitHub and will stop working in 2021.

## 0.4.3

### Patch Changes

- [`1706fb7`](https://github.com/atlassian/changesets/commit/1706fb751ecc2f5a792c42f467b2063078d58716) [#321](https://github.com/atlassian/changesets/pull/321) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Fix TypeScript declarations

## 0.4.2

### Patch Changes

- [`04ddfd7`](https://github.com/atlassian/changesets/commit/04ddfd7c3acbfb84ef9c92873fe7f9dea1f5145c) [#305](https://github.com/atlassian/changesets/pull/305) Thanks [@Noviny](https://github.com/Noviny)! - Add link to changelog in readme

## 0.4.1

### Patch Changes

- [`503154db`](https://github.com/atlassian/changesets/commit/503154db39fe8ab88a1176e4569c48078bcf5569) [#257](https://github.com/atlassian/changesets/pull/257) Thanks [@Noviny](https://github.com/Noviny)! - Modify the Author query to match github's changes to their graphql

* [`16bf3017`](https://github.com/atlassian/changesets/commit/16bf3017dbf25d498fee028bf9806d15edd61be9) [#229](https://github.com/atlassian/changesets/pull/229) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Fix the author of a PR not being queried

## 0.4.0

### Minor Changes

- [`938823f`](https://github.com/atlassian/changesets/commit/938823f6fa0277869f0aecc3345c3812d1e44bba) [#224](https://github.com/atlassian/changesets/pull/224) - Show the PR author of a change rather than the author of the commit that added a changeset to account for cases when maintainers add a changeset to a PR and merge the PR with a merge commit

### Patch Changes

- [`938823f`](https://github.com/atlassian/changesets/commit/938823f6fa0277869f0aecc3345c3812d1e44bba) [#224](https://github.com/atlassian/changesets/pull/224) - Fix cases where the wrong PR is returned when a commit is associated with multiple PRs

## 0.3.0

### Minor Changes

- [`bb855a8`](https://github.com/atlassian/changesets/commit/bb855a869b2d1c4454929b62c3b768546c30d3a3) [#170](https://github.com/atlassian/changesets/pull/170) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Add backticks around commits to be more similar to how commits are shown in GitHub comments

### Patch Changes

- [`bb855a8`](https://github.com/atlassian/changesets/commit/bb855a869b2d1c4454929b62c3b768546c30d3a3) [#170](https://github.com/atlassian/changesets/pull/170) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Convert internals to TypeScript

## 0.2.1

### Patch Changes

- [179433e](https://github.com/atlassian/changesets/commit/179433e3275dc73f6913e2fc2c9134958e084302) [#143](https://github.com/atlassian/changesets/pull/143) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Change query so it works on GitHub Actions and can get the author of a commit even if there isn't an associated pull request

## 0.2.0

### Minor Changes

- [296a6731](https://github.com/atlassian/changesets/commit/296a6731) - Safety bump: Towards the end of preparing changesets v2, there was a lot of chaos - this bump is to ensure every package on npm matches what is found in the repository.

## 0.1.5

### Patch Changes

- [a15abbf9](https://github.com/changesets/changesets/commit/a15abbf9) - Previous release shipped unbuilt code - fixing that

## 0.1.3

### Patch Changes

- [20da7747](https://github.com/changesets/changesets/commit/20da7747) [#66](https://github.com/changesets/changesets/pull/66) Thanks [@Noviny](https://github.com/Noviny)! - Update package.json field so each links into its own package
- [a14f1631](https://github.com/changesets/changesets/commit/a14f1631) [#68](https://github.com/changesets/changesets/pull/68) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Fix GitHub PR link

## 0.1.2

### Patch Changes

- [a966701d](https://github.com/Noviny/changesets/commit/a966701d) - Add repository information to package.json

## 0.1.1

### Patch Changes

- [e0328dc0](https://github.com/Noviny/changesets/commit/e0328dc0) - Previous publish was missing dist, publish with dist.

## 0.1.0

### Minor Changes

- [2e0af049](https://github.com/Noviny/changesets/commit/2e0af049) [#26](https://github.com/Noviny/changesets/pull/26) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Add @changesets/get-github-info package
