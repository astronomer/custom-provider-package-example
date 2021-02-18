# Apache Airflow Custom Provider Example

Example for custom provider package.

## Installation

Pre-requisites: An environment running apache-airflow and GCP access.

Dependencies: `apache-airflow-providers-google`

## Modules

Google Cloud Storage to BigQuery Operator: Operator that extends the capablities of the gcs_to_bq operator from Google Provider package to allow adding of labels to BigQuery table.

```py
from astronomer_provider.transfers.gcs_to_bq import GCSToBigQueryOperator
```