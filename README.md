## Install package
yarn add @rcnp-tickets/common
## Increase patch number to npm package
yarn version --patch

## Publish npm package first time
yarn publish

## Script to add+commit changes to git and publish them as part of a new patch
yarn commit <commit message>
yarn pub
* These two commands work in sequence. They should not be used separately or in the opposite order.

## Update version of library being used in your project
yarn update <package-name>
