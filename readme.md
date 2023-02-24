# Externally Generated Metrics Monitor
This ModelOp Center custom monitor ingests metrics generated via external sources such that they can be ran through model lifecycles and thresholds.

## Input Assets

| Type          | Number | Description                                           |
| ------------- | ------ | ----------------------------------------------------- |
| Baseline Data | **1**  | Externally generated metrics in json format           |

## Assumptions & Requirements
 - This custom monitor assumes the input is a json object of metrics to be tracked and scored later.