# Sentiment Analysis with Caikit and Hugging Face

## Author: Cognitive Class
## 🚀 Mentee Information
| Name             | Program         | Mentor                  |
|------------------|----------------|------------------------|
| Baren Baruna Harahap | MSIB Batch 6 (IBM Advance AI) | Ichsan Takwa       |


Welcome to the Sentiment Analysis project using Caikit and Hugging Face! This project aims to demonstrate how to utilize the Caikit runtime to load and infer a sentiment analysis model provided by Hugging Face. By build this project, you will gain insights into managing AI models efficiently through Caikit's developer-friendly APIs.

## Overview

**Caikit** is an open-source AI toolkit designed to simplify the management of AI models for various tasks and data domains. It offers a consistent format for creating and utilizing AI models, enabling developers to seamlessly integrate AI capabilities into their applications without delving into the complexities of model intricacies.

## Learning Objectives

Upon completion of this lab, We will be able to:

- Install Caikit runtime and required libraries
- Develop a Python client application for Hugging Face sentiment analysis
- Perform sentiment analysis on text samples using the deployed model

## Prerequisites

Before starting this project, ensure we have:

- Linux/MacOS x86_64 environment (provided in Skills Network Lab)
- Caikit (v0.9.2)
- Python (v3.8+)
- pip (v23.0+)

## What We'll Build

We'll construct a Python project consisting of:

- 🛠️ **Caikit runtime**: A data model representing the attributes of the AI model and a model wrapper facilitating model loading and execution.
- 🖥️ **Client application**: Configured to query the AI model for text sentiment analysis using the Caikit runtime.
- 📁 **Directory structure**:

    ```plaintext
    text-sentiment/                  # Top-level package directory
    ├── 🚀 start_runtime.py           # Wrapper to initiate Caikit runtime as a gRPC server
    ├── 🖥️ client.py                  # Client application calling Caikit runtime for inference
    ├── 📋 requirements.txt           # Library dependencies
    ├── 📁 models/                    # Contains Caikit metadata and required artifacts
    │   └── text_sentiment/
    │       └── config.yml            # Metadata defining Caikit text sentiment model
    └── 📁 text_sentiment/            # Defines Caikit module(s) including algorithm implementation
        ├── __init__.py               # Visibility declaration
        ├── config.yml                # Configuration for module and model IO
        ├── 🗃️ data_model/             # Data format for Caikit module
        │   ├── classification.py     # Data class representing AI model attributes
        │   └── __init__.py           # Visibility declaration
        └── 🛠️ runtime_model/          # Caikit module for the model
            └── hf_module.py          # Class bootstrapping the AI model in Caikit

## Documentation

To set up and run the Sentiment Analysis project, follow these steps:

#### Install the Requirements
    pip install -r requirements.txt
#### Start the Runtime
    python start_runtime.py
#### Run the Sentiment Analysis
##### In another terminal tab, execute:
    python client.py

## 📧 Support

For any questions or issues regarding this project, feel free to contact me at [barenbarunaharahap@gmail.com](mailto:barenbarunaharahap@gmail.com).

## 🙏 Acknowledgements

Special thanks to IBM Advance AI @Infinite Learning for providing valuable insights and guidance throughout this course.
