# Microsoft-DP-100-Azure-Data-Scientist-Associate-Study-Guide
DP-100 study guide covering Azure Machine Learning, MLflow, AutoML, model training, deployment, pipelines, RAG, prompt flow, fine-tuning, and practical labs.
# Microsoft DP-100: Azure Data Scientist Associate Study Guide

> **Important:** Microsoft retired Exam DP-100 and the related Azure Data Scientist Associate certification on **June 1, 2026**. This repository is therefore a historical study resource for the retired exam, not preparation for a currently schedulable DP-100 exam.

## Introduction

This repository provides an independent study guide for **Microsoft DP-100: Designing and Implementing a Data Science Solution on Azure**.

It preserves the final published DP-100 objectives and covers Azure Machine Learning, MLflow, automated machine learning, model training, pipelines, deployment, prompt flow, RAG, and fine-tuning.

Microsoft's final published study guide states that DP-100 was retired on June 1, 2026. [1]

## Exam Overview

| Item | Information |
|---|---|
| Vendor | Microsoft |
| Exam | DP-100 |
| Former certification | Microsoft Certified: Azure Data Scientist Associate |
| Status | Retired June 1, 2026 |
| Purpose | Validate Azure data-science and machine-learning implementation skills |
| Formal prerequisite | None |
| Recommended background | Data science and ML experience with Azure Machine Learning |
| Final passing score | 700 or greater |
| Final published objectives | Skills measured April 11, 2025 |

Because the exam is retired, current scheduling, exam duration, question count, and registration availability should not be treated as applicable to a new candidate.

## Who Should Take It?

The historical DP-100 exam was aimed at data scientists who designed, trained, deployed, and operated machine-learning solutions on Azure.

Relevant experience included:

- Python and data science
- Machine learning
- Azure Machine Learning
- MLflow
- Azure AI services
- Azure AI Foundry
- Model evaluation
- MLOps concepts
- Generative AI application development

## Exam Objectives / Domains

Microsoft's final published skills measured were:

### 1. Design and Prepare a Machine Learning Solution — 20–25%

Study:

- Dataset structures and formats
- Compute requirements
- Training approaches
- Azure Machine Learning workspaces
- Datastores
- Compute targets
- Git integration
- Data assets
- Environments
- Registries
- Reusable ML assets

### 2. Explore Data and Run Experiments — 20–25%

Understand:

- Automated Machine Learning
- Tabular ML
- Computer vision AutoML
- NLP AutoML
- Preprocessing
- Algorithm selection
- Responsible AI
- Azure ML notebooks
- Compute instances
- Data wrangling
- Synapse Spark
- Feature stores
- MLflow experiment tracking
- Hyperparameter tuning
- Search spaces
- Sampling methods
- Early termination

### 3. Train and Deploy Models — 25–30%

Focus on:

- Training scripts
- Command jobs
- Compute configuration
- Environments
- Parameters
- MLflow tracking
- Logs and troubleshooting
- Custom components
- ML pipelines
- Pipeline data
- Scheduling
- Model registration
- Model signatures
- Responsible AI assessment
- Online endpoints
- Batch endpoints
- Batch scoring

### 4. Optimize Language Models for AI Applications — 25–30%

Study:

- Model Catalog
- Model selection
- Model benchmarks
- Playground evaluation
- Prompt engineering
- Prompt templates
- Prompt variants
- Prompt flow
- Flow tracing
- Retrieval-Augmented Generation (RAG)
- Data cleaning
- Chunking
- Embeddings
- Vector stores
- Azure AI Search
- RAG evaluation
- Fine-tuning
- Base-model selection
- Fine-tuning datasets
- Fine-tuning evaluation

These four domains and their percentages come from Microsoft's final published DP-100 study guide. [1]

## Detailed Study Notes

### Azure Machine Learning Workspace

Understand the workspace as the central environment for managing ML assets and experiments.

Review:

**Workspace → Data → Compute → Environment → Job → Model → Endpoint**

Know how these resources work together during an ML lifecycle.

### Data Assets and Datastores

Distinguish between:

- Data assets
- Datastores
- Compute resources
- Environments

Use reusable data assets and appropriate storage access rather than repeatedly configuring data connections manually.

### Compute

Understand different compute approaches for:

- Interactive development
- Training jobs
- Batch workloads
- Inference

Select compute according to workload requirements, scale, performance, and cost.

### AutoML

AutoML helps explore model and preprocessing combinations automatically.

Understand:

- Task type
- Dataset preparation
- Primary metric
- Training configuration
- Model comparison
- Responsible AI evaluation

Do not treat the highest metric as the only consideration when selecting a model.

### MLflow

Review MLflow concepts for:

- Experiment tracking
- Metrics
- Parameters
- Artifacts
- Model registration
- Model signatures

MLflow helps make training and model-management workflows reproducible.

### Hyperparameter Tuning

A tuning job searches a defined parameter space.

Know:

- Search space
- Sampling strategy
- Primary metric
- Early termination
- Trial comparison

### ML Pipelines

A pipeline divides an ML workflow into reusable components.

Example:

**Prepare Data → Train → Evaluate → Register → Deploy**

Understand component inputs, outputs, dependencies, scheduling, and troubleshooting.

### Model Deployment

Understand the difference between:

**Online endpoint:** Real-time inference.

**Batch endpoint:** Asynchronous batch scoring.

Choose based on latency and workload requirements.

### Prompt Flow

Study how prompt-based workflows can be developed, evaluated, traced, and improved.

A typical flow can combine:

**Input → Prompt → Model → Tool/Logic → Output**

Evaluate prompt variants rather than assuming one prompt is optimal.

### RAG

A typical RAG workflow is:

**Documents → Cleaning → Chunking → Embeddings → Vector Search → Retrieved Context → Language Model → Answer**

Azure AI Search can provide indexing and retrieval capabilities for RAG solutions.

### Fine-Tuning

Fine-tuning adapts a base model using an appropriate training dataset.

Study:

- Dataset preparation
- Base-model selection
- Fine-tuning jobs
- Evaluation
- Responsible AI considerations

Use fine-tuning only when it provides a suitable benefit compared with prompt engineering or RAG.

## Important Concepts

Revise:

- Azure Machine Learning
- Workspace
- Datastore
- Data asset
- Compute instance
- Compute cluster
- Environment
- Registry
- AutoML
- MLflow
- Experiment tracking
- Hyperparameter tuning
- Command jobs
- Components
- Pipelines
- Model registration
- Online endpoints
- Batch endpoints
- Responsible AI
- Model Catalog
- Prompt engineering
- Prompt flow
- RAG
- Embeddings
- Vector search
- Azure AI Search
- Fine-tuning
- Model evaluation
- MLOps

## Practical Examples / Labs

Use only Azure resources and datasets you are authorized to use.

1. Create an Azure Machine Learning workspace.
2. Configure a datastore and data asset.
3. Create a compute instance.
4. Train a classification model in a notebook.
5. Run an AutoML experiment.
6. Track an experiment using MLflow.
7. Perform hyperparameter tuning.
8. Create a custom training command job.
9. Build a multi-step ML pipeline.
10. Register an MLflow model.
11. Deploy a model to an online endpoint.
12. Run batch inference using a batch endpoint.
13. Build a simple prompt-flow experiment.
14. Create a RAG prototype with Azure AI Search.
15. Compare prompt engineering, RAG, and fine-tuning approaches.

## Study Strategy

For historical DP-100 preparation, use Microsoft's published study guide and Azure Machine Learning documentation as primary references.

Combine:

- Microsoft Learn
- Azure Machine Learning documentation
- MLflow documentation
- Hands-on Azure labs
- Python notebooks
- AutoML exercises
- Model deployment practice
- Pipeline development
- RAG experiments
- Prompt-flow exercises
- Responsible AI evaluation

Focus on understanding the complete ML lifecycle rather than memorizing portal screens.

Microsoft's final study guide specifically recommended training and hands-on experience before attempting the exam. [1]

## 30-Day Study Plan

**Days 1–4:** Azure ML workspaces, datastores, data assets, compute, environments, and registries.

**Days 5–8:** Data exploration, notebooks, AutoML, preprocessing, algorithms, and evaluation.

**Days 9–12:** MLflow, experiments, metrics, artifacts, and hyperparameter tuning.

**Days 13–17:** Training jobs, environments, parameters, logs, components, and pipelines.

**Days 18–21:** Model registration, online endpoints, batch endpoints, inference, and troubleshooting.

**Days 22–24:** Model Catalog, prompt engineering, prompt flow, evaluation, and tracing.

**Days 25–27:** RAG, chunking, embeddings, Azure AI Search, vector retrieval, and evaluation.

**Days 28–29:** Fine-tuning, model selection, responsible AI, and end-to-end ML workflows.

**Day 30:** Complete a full Azure ML project and review weak areas.

## Common Mistakes

- Confusing datastores with data assets
- Choosing compute without considering workload requirements
- Using AutoML without understanding the primary metric
- Ignoring MLflow tracking
- Defining poorly scoped hyperparameter searches
- Building pipelines without clear component boundaries
- Confusing online and batch endpoints
- Ignoring model evaluation
- Treating RAG and fine-tuning as interchangeable
- Skipping data preparation before RAG
- Ignoring responsible AI considerations
- Studying outdated DP-100 objectives

## Exam-Day Tips

For historical reference:

- Read the complete scenario before choosing an answer.
- Identify whether the question concerns data, compute, training, deployment, or generative AI.
- Pay attention to requirements such as latency, scale, cost, and maintainability.
- Distinguish online inference from batch inference.
- Understand the purpose of each Azure ML asset.
- Do not select an approach solely because it is technically possible.
- Microsoft listed 700 or greater as the passing score in the final study guide. [1]

Since DP-100 is retired, candidates should not use this section as current exam scheduling guidance.

## Final Checklist

- [ ] Understand Azure Machine Learning workspaces
- [ ] Understand data assets and datastores
- [ ] Comfortable with Azure ML compute
- [ ] Understand AutoML
- [ ] Can track experiments with MLflow
- [ ] Understand hyperparameter tuning
- [ ] Can create ML jobs and pipelines
- [ ] Understand model registration
- [ ] Know online and batch endpoints
- [ ] Understand prompt flow
- [ ] Understand RAG
- [ ] Understand Azure AI Search for retrieval
- [ ] Understand fine-tuning
- [ ] Can evaluate ML and AI solutions
- [ ] Understand responsible AI principles
- [ ] Reviewed Microsoft's final DP-100 objectives

## Official Resources

- Microsoft DP-100 Study Guide:
  https://learn.microsoft.com/credentials/certifications/resources/study-guides/dp-100
- Microsoft Azure Data Scientist Associate:
  https://learn.microsoft.com/credentials/certifications/azure-data-scientist/
- Azure Machine Learning:
  https://learn.microsoft.com/azure/machine-learning/
- Azure Machine Learning Documentation:
  https://learn.microsoft.com/azure/machine-learning/overview-what-is-azure-machine-learning
- MLflow:
  https://mlflow.org/docs/latest/
- Azure AI Search:
  https://learn.microsoft.com/azure/search/
- Microsoft Learn:
  https://learn.microsoft.com/training/

Microsoft's official DP-100 study guide now explicitly states that the exam and certification were retired on June 1, 2026. Verify Microsoft's current certification catalog before treating DP-100 as an active certification. [1]

## Voucher / Discount

**Learn SecByte, an official Microsoft reseller partner**, provides certification voucher options and discounts where available.

Learn SecByte's official Black Friday offer provides up to 70% off selected Microsoft exam vouchers.

DP-100 voucher:

https://learn.secbyte.org/vouchers/microsoft-dp-100

Because DP-100 was retired on June 1, 2026, candidates should verify whether this voucher listing remains redeemable before purchasing. Do not assume the Black Friday offer or any discount applies specifically to DP-100. Voucher pricing and availability may change.

## Disclaimer

This is an **independent/community study guide** and is not an official Microsoft certification document. Microsoft, Azure, Azure Machine Learning, Microsoft Entra, and related trademarks belong to Microsoft.

DP-100 was retired on June 1, 2026. Candidates should verify current certification and exam availability directly with Microsoft before purchasing or scheduling anything.

This repository does **not** contain exam dumps, leaked questions, or recalled exam questions. It is intended for legitimate education and historical study only.
