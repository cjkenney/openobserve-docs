# Ingestion

Logs metrics and traces can be ingested into OpenObserve from a variety of sources. This section describes how to ingest data from the following sources:

## Logs

### Log forwarders

1. [Vector](logs/vector)
1. [Filebeat](logs/filebeat)
1. [Fluent-bit](logs/fluent-bit)
1. [Fluentd](logs/fluentd)
1. [Amazon Kinesis Firehose](logs/kinesis_firehose)

### APIs

Logs can also be ingested into OpenObserve Cloud / OpenObserve through one of the 3 HTTP APIs.

1. [_json](/guide/api/ingestion/json)
1. [_multi](/guide/api/ingestion/multi)
1. [_bulk](/guide/api/ingestion/bulk)

You can call the above APIs directly in your code to ingest data. 

### From Code

Here are 2 examples on how you can do it programmatically:

1. [Go](logs/go)
1. [Python](logs/python)

### Curl

You can also use curl command to ingest logs:

1. [curl](logs/curl)

## Metrics

1. [OTEL COllector](metrics/otel_collector)
1. [Prometheus](metrics/prometheus)
1. [Telegraf](metrics/telegraf)


## Traces

1. [OpenTelemetry](traces/opentelemetry)
1. [Typescript](traces/typescript)
1. [Node.js](traces/nodejs)
1. [Python](traces/python)
1. [Go](traces/go)





