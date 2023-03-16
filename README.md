# Problem

Using workspaces can you select a particular version?

For example the top level package.json is:

    "@kaihendry/private-pkg-test": "^1.0.0"

However the actual [workspace package.json](https://github.com/kaihendry/npm-workspaces-test/blob/main/packages/private-pkg-test/package.json#L3) is 2.0.0.

I would prefer in this case that `npm i` fetches the partcular version from https://gitlab.com/kaihendry/private-pkg-test !
