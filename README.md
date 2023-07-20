# docker-action-demo
Action to show that you can create an action without an action.yml file. Publishing to the marketplace requires an `action.yml` file, but can be removed after publishing. Publishing a new version is not possibe then, without an `action.yml` file 😢.

The runner does not care about the marketplace, and just looks at the action repo for `action.yml`, `action.yaml`, `Dockerfile`, or `dockerfile` in the root of the repository or folder that you are executing.
