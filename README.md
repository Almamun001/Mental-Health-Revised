# Mental Health Text Classification - Revised

This repository contains advanced machine learning models for mental health text classification using hybrid neural network architectures.

## Overview

The repository includes three Jupyter notebooks implementing different approaches to mental health text classification:

1. **MentalBERT_BiLSTM_CNN_(Re_Revised).ipynb** - Latest and most comprehensive version
2. **MentalBERT_BiLSTM_CNN_(Revised).ipynb** - Previous version 
3. **Hybrid_Mental_Health_Classifier.ipynb** - Alternative implementation

## Key Features

- **Hybrid Architecture**: Combines MentalBERT, BiLSTM, and CNN for robust classification
- **Domain-Specific**: Uses MentalBERT pre-trained on mental health text
- **Large Dataset**: 52,681 mental health text statements
- **Google Colab Ready**: Optimized for cloud-based training

## Quick Start

1. Open any notebook in Google Colab
2. Mount Google Drive for dataset access
3. Install required dependencies
4. Run the complete pipeline

## Documentation

- [Detailed Analysis](NOTEBOOK_ANALYSIS.md) - Comprehensive overview of the main notebook
- [Technical Summary](TECHNICAL_SUMMARY.md) - Quick technical reference

## Model Architecture

```
Text Input → MentalBERT → BiLSTM + CNN → Feature Fusion → Classification
```

The hybrid approach leverages:
- **MentalBERT**: Contextual understanding of mental health terminology
- **BiLSTM**: Sequential pattern recognition
- **CNN**: Local feature extraction

## Requirements

- TensorFlow 2.15.0
- Transformers library
- Google Colab environment (recommended)
- GPU acceleration (recommended)