# Machine-Description-Generator
AI-powered system for generating technical equipment descriptions from structured data and PDF documentation.

## Features
- 🤖 Llama-3.2-3B language model integration
- 📄 PDF document parsing and context extraction
- 🚀 FAISS vector database for technical specifications
- 🌐 Multilingual support with automatic translation
- 📊 Excel data processing pipeline

## Installation

git clone https://github.com/Meenakshi2434/Machine-Description-Generator.git
cd your-repo-name
pip install -r requirements.txt
Usage
Prepare input data:
data/
├── input/data.xlsx
└── pdfs/[manufacturer]/[model]/documentation.pdf

## Run the processor:
python src/machine_description_generator.py
Data Requirements
MD_data.xlsx - Machine specifications
manufacturer_mapping.xlsx - Manufacturer ID mappings
model_mapping.xlsx - Model ID mappings

## Output
- Generates output_machines_with_descriptions.xlsx with:
- AI-generated technical descriptions
- Source documentation references
- Confidence scores
