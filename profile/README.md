# CloudStub

[![Documentation](https://img.shields.io/static/v1?label=Documentation&message=public&color=green)](https://cloudstub.github.io/cloudstub)
[![Maven Central](https://img.shields.io/static/v1?label=Maven+Central&message=io.github.cloudstub&color=blue)](https://central.sonatype.com/namespace/io.github.cloudstub)
[![License](https://img.shields.io/github/license/cloudstub/cloudstub)](https://github.com/cloudstub/cloudstub/blob/main/LICENSE)

In-process AWS mocking for the JVM. No Docker. No external process. No configuration.

CloudStub is an open source AWS mock framework for the JVM. It intercepts AWS SDK calls
and returns realistic responses without connecting to AWS, running a container, or starting
an external process. Each AWS service is an independent module — add only what you need,
nothing more loads.

CloudStub runs entirely inside the JVM, starts in milliseconds, and loads only the service
modules your project declares as dependencies. Drop it in, write your test, run it.

## Repositories

| Repository                                                          | Description                              |
|---------------------------------------------------------------------|------------------------------------------|
| [cloudstub](https://github.com/cloudstub/cloudstub)                 | Core framework, service modules, codegen |
| [cloudstub-cli](https://github.com/cloudstub/cloudstub-cli)         | CLI tool — `clm`                         |
| [cloudstub-console](https://github.com/cloudstub/cloudstub-console) | Web UI for standalone mode               |

## Contributing

If a module you need doesn't exist yet, you can build it.
See the [module authoring guide](https://cloudstub.github.io/cloudstub) to get started.
