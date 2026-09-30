# Outcomes Insights

We design and analyze studies that use electronic health data, and we build software
that makes that research easier to do well. Most of that software starts as something we
needed ourselves; the pieces that are useful beyond our own work live here as open source.

Our main product is [Jigsaw](https://jigsaw.io), software for creating analysis-ready
datasets from healthcare data. The ideas underneath it — a common data model and a
language for stating research algorithms without ambiguity — are the open-source
projects below.

## Open source

### The model and the language

| Project | What it is |
|---|---|
| [generalized_data_model](https://github.com/outcomesinsights/generalized_data_model) | The Generalized Data Model (GDM): our data model for clinical research, designed to represent healthcare data faithfully so it can be analyzed reliably. |
| [conceptql](https://github.com/outcomesinsights/conceptql) | ConceptQL, a high-level language that lets researchers define their algorithms unambiguously, so a cohort definition means the same thing to everyone who reads it. |
| [conceptql_spec](https://github.com/outcomesinsights/conceptql_spec) | The ConceptQL language specification. |
| [vocabulary_formats](https://github.com/outcomesinsights/vocabulary_formats) | Patterns that verify the codes used in medical terminologies are well formed. |

### Working with public health datasets in R

| Project | What it is |
|---|---|
| [nhanes.tools](https://github.com/outcomesinsights/nhanes.tools) | Load and use NHANES data without the usual friction. |
| [seermedicare](https://github.com/outcomesinsights/seermedicare) | Visualization tools for SEER-Medicare publications data. |
| [seer.tools](https://github.com/outcomesinsights/seer.tools) | Download and use SEER data from NCI. |
| [namcs_nhamcs_tools](https://github.com/outcomesinsights/namcs_nhamcs_tools) | Download and load NAMCS and NHAMCS data. |
| [seer_to_omop_cdmv4](https://github.com/outcomesinsights/seer_to_omop_cdmv4) | A partial ETL of SEER-Medicare data into the OMOP CDM. |

### Database tooling in Ruby

| Project | What it is |
|---|---|
| [sequelizer](https://github.com/outcomesinsights/sequelizer) | Establish a [Sequel](https://sequel.jeremyevans.net) database connection from configuration, quickly. |
| [sequel-duckdb](https://github.com/outcomesinsights/sequel-duckdb) | A Sequel adapter for DuckDB. |
| [sequel-hexspace](https://github.com/outcomesinsights/sequel-hexspace) | A Sequel adapter for Hexspace (Spark Thrift). |

### Utilities

| Project | What it is |
|---|---|
| [sas2yaml](https://github.com/outcomesinsights/sas2yaml) | Convert SAS input statements into YAML describing a dataset's layout. |
| [sparkopy](https://github.com/outcomesinsights/sparkopy) | Download tables from Spark as Parquet files. |
| [seeds](https://github.com/outcomesinsights/seeds) | Git-backed capture of the deliberation behind a codebase, for ideas that need time to grow. |

## The blog

[jigsaw.io](https://jigsaw.io) is where we write about developing software for generating
real-world evidence from real-world data: data management, common data models, ETL, code
standardization, and the algorithms behind healthcare data analysis.

## Elsewhere

- Company site: [outins.com](https://www.outins.com)
- Blog: [jigsaw.io](https://jigsaw.io)
