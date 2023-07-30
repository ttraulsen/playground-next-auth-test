# next-auth test playground

This is just a little playground to fool around with next-auth. It will require
to run some oauth server (e.g. keycloak) additionally. The goal is to use roles
within some jwt to control available functions.

## how to run

1. have some keycloak running
2. `yarn install`
3. update the configuration URL
4. `yarn run dev`
