[![Build Status](https://github.com/asottile/set-delete-branch-on-merge/workflows/main/badge.svg)](https://github.com/asottile/set-delete-branch-on-merge/actions)
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/asottile/set-delete-branch-on-merge/master.svg)](https://results.pre-commit.ci/latest/github/asottile/set-delete-branch-on-merge/master)

set-delete-branch-on-merge
==========================

github does not provide a way to set the `delete_branch_on_merge` as a default.

this tool runs using periodic github actions to set that property on your
repositories.

to use this:
- fork this repository
- create a [personal access token]
- create a repository secret: `GH_TOKEN`
- enable github actions
- modify the `ORGS` setting in `./set-delete-branch-on-merge`
- enjoy!

[personal access token]: https://github.com/settings/tokens/new
