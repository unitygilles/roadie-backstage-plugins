# @roadiehq/backstage-plugin-buildkite

## 2.1.15

### Patch Changes

- c6b0af08: Bump plugins version to backstage version 1.18.3

## 2.1.14

### Patch Changes

- 0d688d09: Bump package versions to backstage version 1.17.0

## 2.1.13

### Patch Changes

- 05c0c417: Update deps to backstage 1.16.0 version

## 2.1.12

### Patch Changes

- edf2f0ab: Update dependencies to backstage version 1.15.0

## 2.1.11

### Patch Changes

- 608e1061: Release all

## 2.1.10

### Patch Changes

- 59179c45: Upgrade to backstage version 1.14.1

## 2.1.9

### Patch Changes

- 85620abc: Bump packages to backstage version 1.13.0

## 2.1.8

### Patch Changes

- e331d3a1: Bump to backstage version 1.12.1

## 2.1.7

### Patch Changes

- f129477d: Upgrade to backstage 1.12.0

## 2.1.6

### Patch Changes

- ac5717e6: Update plugins to Backstage version 1.11.1

## 2.1.5

### Patch Changes

- 1599cf96: release dependabot PRs

## 2.1.4

### Patch Changes

- 3a870726: Bump the `msw` dependency to `^1.0.1`

## 2.1.3

### Patch Changes

- 6d186f0f: Bump plugin's version to backstage version 1.10.1

## 2.1.2

### Patch Changes

- 054d585b: Bump plugin versions to be compatible by backstage 1.9.1

## 2.1.1

### Patch Changes

- 7084d814: Bump plugins version to backstage 1.8.3

## 2.1.0

### Minor Changes

- 015aebdf: Bump plugins version to be compatible by backstage 1.7

## 2.0.9

### Patch Changes

- eaa0bb2: update dependencies

## 2.0.8

### Patch Changes

- 99153fe: Move react-router and react-router-dom dependencies to peerDependencies because of the migration to the stabel version of react-router in backstage/backstage. See the migration guide [here](https://backstage.io/docs/tutorials/react-router-stable-migration#for-plugin-authors)

## 2.0.7

### Patch Changes

- 151b46b: bump to latest backstage package versions

## 2.0.6

### Patch Changes

- c9cfaad: Release all plugins after fixing typescript exports issue.

## 2.0.5

### Patch Changes

- 86eca6a: Update dependencies

## 2.0.4

### Patch Changes

- b424a98: Handle Buldkite Jobs with type of 'waiter'

## 2.0.3

### Patch Changes

- 6e0c293: Utilize fetchApi core plugin over native fetch

## 2.0.2

### Patch Changes

- 1a22089: Fix the '/builds/:buildNumber' route, to be displayed

## 2.0.1

### Patch Changes

- 6b4cc16: Update dependencies
  Add package information to the package.jsons, to tell the backstage cli how to run the tests

## 2.0.0

### Major Changes

- df841f0: Update dependecies to follow latest upstream version. Removed deprecated props of type 'Entity' passed into components as it is grabbed from context instead.

## 1.4.0

### Minor Changes

- f0421b4: Bumped to the latest upstream packages versions

## 1.3.13

### Patch Changes

- 5a2757c: Change notice headers to contain Larder Software Limited

## 1.3.12

### Patch Changes

- f5cd7e4: Update dependencies to latest Backstage packages

## 1.3.11

### Patch Changes

- 46b19a3: Update dependencies

## 1.3.10

### Patch Changes

- c779d9e: Update dependencies

## 1.3.9

### Patch Changes

- 7da7bfe: Update dependencies

## 1.3.8

### Patch Changes

- 5ae1b4b: Update README.md files

## 1.3.7

### Patch Changes

- b5db653: Update dependecies to latest packages

## 1.3.6

### Patch Changes

- a02dbf5: Migrating to TestApiProvider in the tests

## 1.3.5

### Patch Changes

- 142ce1c: Moved React dependencies to `peerDependencies` and allow both React v16 and v17 to be used.

## 1.3.4

### Patch Changes

- b586451: Switch to using LogViewer from '@backstage/core-components'.

## 1.3.3

### Patch Changes

- ecd06f5: Make "@backstage/core-app-api" a dev dependency

## 1.3.2

### Patch Changes

- 49abec7: Update patch to release new changes.

## 1.3.1

### Patch Changes

- a728fd1: Update underlying packages and release.

## 1.3.0

### Minor Changes

- ed90f25: Breaking dependency updates for @backstage/core-app-api, @backstage/test-utils, @backstage/core-plugin-api, @backstage/backend-common && @backstage/integration

## 1.2.4

### Patch Changes

- 773692a: Change default port of backend from 7000 to 7007.

  This is due to the AirPlay Receiver process occupying port 7000 and preventing local Backstage instances on MacOS to start.

## 1.2.3

### Patch Changes

- 120ca2e: Removed deprecated `description` option from `ApiRefConfig` for all plugins

## 1.2.2

### Patch Changes

- 4d426f9: Updated dependencies to follow latest Backstage release

## 1.2.1

### Patch Changes

- 3f280ef: Updated 'msw' package version in order to correctly run tests.
