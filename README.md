Library of Error definitions, middlewares, and different type of handlers used by the microservices that compound the ticketing solution. 
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

## Update version of dependency library being used in your project
yarn update <package-name> (updates only the yarn.lock file)
yarn install <package-name>@latest (updates the version showed in package.json file)

## go inside shell of a specific POD

### Find out first the POD name
kubectl get pods
### Then use it in this command
kubectl exec -it <pod-name> sh