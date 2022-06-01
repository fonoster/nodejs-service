# Fonoster {Service Name}

> {A short description of the image, same as the Github Repo description.}

{Badges should all be in one row without carriage returns. Replace the {name} with your docker image name.}

![publish to docker](https://github.com/fonoster/nodejs-service/workflows/publish%20to%20docker%20hub/badge.svg)

{Longer description of what the image provides.}

For more documentation on how Fonos images are constructed and how to work with them, please see the [documentation](https://github.com/fonoster/fonoster).

## Available Versions

{Keep this as-is, but replace {name} with your Docker image name.}

You can see all images available to pull from Docker Hub via the [Tags]() page. Docker tag names that begin with a "change type" word such as task, bug, or feature are available for testing and may be removed at any time.

## Installation

You can clone this repository and manually build it.

```
cd fonoster/{service}\:%%VERSION%%
docker build -t fonoster/{service}:%%VERSION%% .
```

Otherwise you can pull this image from docker index.

```
docker pull fonoster/{service}:%%VERSION%%
```

## Usage Example

{An example of running the container. Most Fonoster-based services use docker-compose, so that kind of example is preferred but a docker run is also very helpful.}

The following is a basic example of using this image.

```
docker run ...
```

## Specs

Optional specification notes.

{List of packages and tools, H3 section breakouts for more detail}

## Environment Variables

Environment variables are used in the entry point script to render configuration templates. You can specify the values of these variables during `docker run`, `docker-compose up`, or in Kubernetes manifests in the `env` array.

{Each environment variable might have 1-2 sentences of description. If it needs longer than that, it should probably have a sub-section within Specs to elaborate.}

- `EXAMPLE_VAR2` - Example variable 1. **Required**
- `EXAMPLE_VAR2` - Example optiona variable

## Exposed ports

- `48080` - Default application port for http

## Volumes

- `/your/file/location` - File location
- `/some/special/script.sh` - List special scripts

## Useful File Locations

- `/some/special/script.sh` - List special scripts
- `/magic/dir` - And also directories

## Contributing

Please read [CONTRIBUTING.md](https://github.com/fonoster/fonoster/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

- [Pedro Sanders](https://github.com/psanders)

See also the list of contributors who [participated](https://github.com/fonoster/fonoster/contributors) in this project.

## License

Copyright (C) 2022 by Fonoster Inc. MIT License (see [LICENSE](https://github.com/fonoster/fonoster/blob/master/LICENSE) for details).
