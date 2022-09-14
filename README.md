# typekit

_Write Dockerfiles in TypeScript._

typekit is a portable CI/CD tool. With typekit, you can write Dockerfiles and CI/CD pipelines in
TypeScript, then run them anywhere, be it locally or on a hosted platform.

typekit takes inspiration from tools like [Earthly](https://earthly.dev/),
[Dagger](https://dagger.io/), and [Tangram](https://tangram.dev/).

## Commands

### `typekit preview`

Generate a Dockerfile from a TypeKit build definition.

### `typekit build`

Build a Docker image from a TypeKit build definition.

### `typekit ls`

List the build targets and pipelines from a TypeKit file.

### `typekit run`

Run a TypeKit function.

## What's missing?

- `typekit run` for pipelines.
- `typekit ls` for pipelines.
- Instructions for running locally or on CI.
- An example of running on GitHub Actions.
- An example of using typekit with Pulumi.
- Ability to push images as part of a pipeline.
- Ability to extract artifacts as part of a pipeline.
- Ability to run builds remotely.

## License

MIT
