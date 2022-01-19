# Temporal Worker

This Jupyter Notebook implements a Temporal Workflow Worker as well as a Temporal Activity Worker via the [Temporal API](https://github.com/temporalio/api).

## Introduction

In most cases you will interat with Temporal via the Temporal SDKs (High Level) but this Jupyter Notebook show cases the interaction between Temporal Workers and the Temporal Server via the [Temporal API](https://github.com/temporalio/api) (Low Level)

## Getting Started

Clone repository and execute

```
docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "${PWD}":/home/jovyan dtornow/temporal-notebook:1.0
```

Navigate to

```
http://localhost:8888
```