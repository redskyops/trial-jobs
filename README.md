# StormForge Optimize - Trials

![Main](https://github.com/thestormforge/optimize-trials/workflows/Main/badge.svg)

This repository is a collection of containers suitable for use as trial jobs during an experiment. Each container has specific requirements in terms of experiment setup, consult the individual container's documentation for more details.

## Trial Jobs

### StormForge Performance

The StormForge Performance trial job invokes a [StormForge Performance](https://www.stormforge.io/performance-testing/) test case against your application, with each trial corresponding to a test run.

### Locust

The Locust trial job creates a [Locust](https://locust.io/) load test parametrized via environment variables.
