# Agentic Fix Dataset

This repository contains the dataset CSV files used in our flaky-test repair experiments.

## Dataset

The CSV files in this repository contain the metadata, download URLs for the project archives, and other information required to run the flaky test. The dataset follows the same format and structure as [ReproFlake](https://github.com/mahbubsumon085/ReproFlake).

- [config.csv](./config.csv)

## Hadoop-Related Tests

Some Hadoop-related projects require **Protocol Buffers (protobuf) 2.5.0** to build and execute successfully.

An example Docker image with protobuf 2.5.0 installed is provided in:

- [Dockerfile.nio](./Dockerfile.nio)

Please use this Dockerfile as a reference when preparing the execution environment for Hadoop-based tests.