---
title: OpenTelemetry Demo Docs
linkTitle: Demo
cascade:
  repo: https://github.com/open-telemetry/opentelemetry-demo
weight: 180
cSpell:ignore: OLJCESPC
---

Welcome to the [OpenTelemetry Demo](/ecosystem/demo/) documentation, which
covers how to install and run the demo, and some scenarios you can use to view
OpenTelemetry in action.

## Running the Demo

Want to deploy the demo and see it in action? Start here.

- [Docker](docker-deployment/)
- [Kubernetes](kubernetes-deployment/)

## Language Feature Reference

Want to understand how a particular language's instrumentation works? Start
here.

| Language   | Automatic Instrumentation                          | Instrumentation Libraries                                                                    | Manual Instrumentation                                                                       |
| ---------- | -------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| .NET       | [Accounting Service](services/accounting/)         | [Cart Service](services/cart/)                                                               | [Cart Service](services/cart/)                                                               |
| C++        |                                                    |                                                                                              | [Currency Service](services/currency/)                                                       |
| Go         |                                                    | [Checkout Service](services/checkout/), [Product Catalog Service](services/product-catalog/) | [Checkout Service](services/checkout/), [Product Catalog Service](services/product-catalog/) |
| Java       | [Ad Service](services/ad/)                         |                                                                                              | [Ad Service](services/ad/)                                                                   |
| JavaScript |                                                    |                                                                                              | [Payment Service](services/payment/)                                                         |
| TypeScript |                                                    | [Frontend](services/frontend/), [React Native App](services/react-native-app/)               | [Frontend](services/frontend/)                                                               |
| Kotlin     |                                                    | [Fraud Detection Service](services/fraud-detection/)                                         |                                                                                              |
| PHP        |                                                    | [Quote Service](services/quote/)                                                             | [Quote Service](services/quote/)                                                             |
| Python     | [Recommendation Service](services/recommendation/) |                                                                                              | [Recommendation Service](services/recommendation/)                                           |
| Ruby       |                                                    | [Email Service](services/email/)                                                             | [Email Service](services/email/)                                                             |
| Rust       |                                                    | [Shipping Service](services/shipping/)                                                       | [Shipping Service](services/shipping/)                                                       |

## Service Documentation

Specific information about how OpenTelemetry is deployed in each service can be
found here:

- [Accounting Service](services/accounting/)
- [Ad Service](services/ad/)
- [Cart Service](services/cart/)
- [Checkout Service](services/checkout/)
- [Email Service](services/email/)
- [Frontend](services/frontend/)
- [Load Generator](services/load-generator/)
- [Payment Service](services/payment/)
- [Product Catalog Service](services/product-catalog/)
- [Quote Service](services/quote/)
- [Recommendation Service](services/recommendation/)
- [Shipping Service](services/shipping/)
- [Image Provider Service](services/image-provider/)
- [React Native App](services/react-native-app/)

## Scenarios

How can you solve problems with OpenTelemetry? These scenarios walk you through
some pre-configured problems and show you how to interpret OpenTelemetry data to
solve them.

We'll be adding more scenarios over time.

- Generate a [Product Catalog error](feature-flags) for `GetProduct` requests
  with product ID: `OLJCESPC7Z` using the Feature Flag service
- Discover a memory leak and diagnose it using metrics and traces.
  [Read more](scenarios/recommendation-cache/)

## Reference

Project reference documentation, like requirements and feature matrices.

- [Architecture](architecture/)
- [Development](development/)
- [Feature Flags Reference](feature-flags/)
- [Metric Feature Matrix](telemetry-features/metric-coverage/)
- [Requirements](./requirements/)
- [Screenshots](screenshots/)
- [Services](services/)
- [Span Attributes Reference](telemetry-features/manual-span-attributes/)
- [Tests](tests/)
- [Trace Feature Matrix](telemetry-features/trace-coverage/)
