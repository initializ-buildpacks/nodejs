# Initializ Buildpack for Node.js

## `https://hub.docker.com/r/initializbuildpacks/nodejs`

The Node.js Initializ Buildpack facilitates the construction of Node.js-based applications through a cohesive set of collaborating buildpacks. These buildpacks encompass:
- [Node Engine CNB](https://github.com/initializ-buildpacks/node-engine)
- [Yarn CNB](https://github.com/initializ-buildpacks/yarn)
- [Yarn Install CNB](https://github.com/initializ-buildpacks/yarn-install)
- [NPM Install CNB](https://github.com/initializ-buildpacks/npm-install)
- [Yarn Start CNB](https://github.com/initializ-buildpacks/yarn-start)
- [NPM Start CNB](https://github.com/initializ-buildpacks/npm-start)
- [Node Start CNB](https://github.com/initializ-buildpacks/node-start)

The buildpack provides support for building and running straightforward Node applications, as well as applications that utilize either [NPM](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/) for dependency management. It's worth noting that support for each of these package managers is mutually exclusive.

Usage examples can be found in the
[`samples` repository under the `nodejs` directory](https://github.com/initializ-buildpacks/samples/tree/main/nodejs).

#### The Node.js buildpack is compatible with the following builder(s):
- [Securepacks Builder](https://github.com/initializ-buildpacks/Securepacks)

This buildpack also includes the following utility buildpacks:
- [Procfile CNB](https://github.com/initializ-buildpacks/procfile)
- [Environment Variables CNB](https://github.com/initializ-buildpacks/environment-variables)
- [Image Labels CNB](https://github.com/initializ-buildpacks/image-labels)
- [CA Certificates CNB](https://github.com/initializ-buildpacks/ca-certificates)
- [Node Run Script CNB](https://github.com/initializ-buildpacks/node-run-script)
- [Node Module Bill of Materials CNB](https://github.com/initializ-buildpacks/node-module-bom)

