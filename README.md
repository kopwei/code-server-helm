# CodeServer Helm Chart
This Helm chart is a lightweight way to configure and run [code server](https://github.com/cdr/code-server).

## Requirements

* [Helm][] >=3.0.0
* Kubernetes >=1.8
* Minimum cluster requirements include the following to run this chart with
default settings. All of these settings are configurable.
  * Three Kubernetes nodes to respect the default "hard" affinity settings
  * 1GB of RAM for the JVM heap

## Installing

You can install the helm chart via ordinary Helm process.

```bash
helm install cs code-server -f <PATH/TO/YOUR/VALUES.yaml>
```
