# promdoc

`promdoc` lets you automatically generate documentation from your [PrometheusRules](https://github.com/coreos/prometheus-operator/blob/master/Documentation/design.md#prometheusrule).

```
NOTE: This project is currently a work in progress. 
Feedback, feature requests, and contributions are welcome!
```

## Installation

### From source

`go get github.com/plexsystems/promdoc`

## Usage

Run the following command in the root of your project to create a markdown file named `alerts.md` that contains your Prometheus alerts.

```console
$ promdoc generate alerts.md
```