# Standardized Insurance Policy Structure

This repository aims to create a standardized JSON structure for representing information extracted from health insurance policy documents. The goal is to make policy details more accessible, comparable, and machine-readable.

## Repository Structure
```
├── JSON/                          # Contains JSON files extracted from policy PDFs
│   ├── example_policy_1.json
│   ├── example_policy_2.json
│   └── ...
├── PDFs/                          # Contains the original insurance policy PDF documents
│   ├── example_policy_1.pdf
│   ├── example_policy_2.pdf
│   └── ...
│
├── JSON template.json             # Defines the standard schema/template for the JSON files
└── README.md                      # This file
```

## The JSON Template (`JSON template.json`)

The `JSON template.json` file serves as the blueprint for all JSON files in the `JSON/` directory. It defines the expected keys, data types, and structure for capturing policy details. Please refer to this file for the exact schema.