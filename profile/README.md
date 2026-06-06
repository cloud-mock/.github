# CloudMock

[![Documentation](https://img.shields.io/static/v1?label=Documentation&message=public&color=green)](https://cloud-mock.github.io/cloud-mock)
[![Maven Central](https://img.shields.io/static/v1?label=Maven+Central&message=io.github.cloud-mock&color=blue)](https://central.sonatype.com/namespace/io.github.cloud-mock)
[![License](https://img.shields.io/github/license/cloud-mock/cloud-mock)](https://github.com/cloud-mock/cloud-mock/blob/main/LICENSE)

In-process AWS mocking for the JVM. No Docker. No external process. No configuration.

CloudMock is an open source AWS mock framework for the JVM. It intercepts AWS SDK calls
and returns realistic responses without connecting to AWS, running a container, or starting
an external process. Each AWS service is an independent module — add only what you need,
nothing more loads.

CloudMock runs entirely inside the JVM, starts in milliseconds, and loads only the service
modules your project declares as dependencies. Drop it in, write your test, run it.

## Repositories

| Repository | Description |
|---|---|
| [cloud-mock](https://github.com/cloud-mock/cloud-mock) | Core framework, service modules, codegen |
| [cloudmock-cli](https://github.com/cloud-mock/cloudmock-cli) | CLI tool — `clm` |
| [cloudmock-console](https://github.com/cloud-mock/cloudmock-console) | Web UI for standalone mode |

## Contributing

If a module you need doesn't exist yet, you can build it.
See the [module authoring guide](https://cloud-mock.github.io/cloud-mock) to get started.
