![diagrams logo](assets/img/diagrams.png)

# Diagrams

[![license](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)
[![pypi version](https://badge.fury.io/py/diagrams.svg)](https://badge.fury.io/py/diagrams)
![python version](https://img.shields.io/badge/python-3.6%2C3.7%2C3.8-blue?logo=python)
![on premise provider](https://img.shields.io/badge/provider-OnPremise-orange?color=5f87bf)
![aws provider](https://img.shields.io/badge/provider-AWS-orange?logo=amazon-aws&color=ff9900)
![azure provider](https://img.shields.io/badge/provider-Azure-orange?logo=microsoft-azure&color=0089d6)
![gcp provider](https://img.shields.io/badge/provider-GCP-orange?logo=google-cloud&color=4285f4)
![kubernetes provider](https://img.shields.io/badge/provider-Kubernetes-orange?logo=kubernetes&color=326ce5)
![alibaba cloud provider](https://img.shields.io/badge/provider-AlibabaCloud-orange)
![oracle cloud provider](https://img.shields.io/badge/provider-OracleCloud-orange?logo=oracle&color=f80000)

**Diagram as Code**.

Diagrams lets you draw the cloud system architecture **in Python code**. It was born for **prototyping** a new system architecture design without any design tools. You can also describe or visualize the existing system architecture as well. Diagrams currently supports six major providers: `AWS`, `Azure`, `GCP`, `Kubernetes`, `Alibaba Cloud` and `Oracle Cloud`.  It now also supports `On-Premise` nodes.

**Diagram as Code** also allows you to **tracking** the architecture diagram changes on any **version control** system.

>  NOTE: It does not control any actual cloud resources nor generate cloud formation or terraform code, but just for drawing the cloud system architecture diagrams.

## Getting Started

It uses [Graphviz](https://www.graphviz.org/) to render the diagram, so you need to [install Graphviz](https://graphviz.gitlab.io/download/) to use **diagrams**. After installing graphviz (or already have it), install the **diagrams**.

> macOS users can download the Graphviz via `brew install graphviz` if you're using [Homebrew](https://brew.sh).

```shell
# using pip (pip3)
$ pip install diagrams

# using pipenv
$ pipenv install diagrams

# using poetry
$ poetry add diagrams
```

You can start with [quick start](https://diagrams.mingrammer.com/docs/getting-started/installation#quick-start). Check out [guides](https://diagrams.mingrammer.com/docs/guides/diagram) for more details, and you can find all available nodes list in [here](https://diagrams.mingrammer.com/docs/nodes/aws).

## Examples

| Event Processing                                             | Stateful Architecture                                        | Advanced Web Service                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![event processing](https://diagrams.mingrammer.com/img/event_processing_diagram.png) | ![stateful architecture](https://diagrams.mingrammer.com/img/stateful_architecture_diagram.png) | ![advanced web service with on-premise](https://diagrams.mingrammer.com/img/advanced_web_service_with_on-premise.png) |

You can find all the examples on the [examples](https://diagrams.mingrammer.com/docs/getting-started/examples) page.

## Contributing

To contribute to diagram, check out [contribution guidelines](CONTRIBUTING.md).

> Let me know if you are using diagrams! I'll add you in showcase page. (I'm working on it!) :)

## License

[MIT](LICENSE)
