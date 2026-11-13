# Learning Transformers

A hands-on learning repository for exploring Hugging Face Transformers, datasets, and practical NLP workflows. The notebooks cover everything from using pretrained models with pipelines to preparing datasets, fine-tuning BERT, and building a semantic search index.

## Notebooks

### Transformers pipelines
- [`pipeline_in_transformers.ipynb`](notebooks/pipeline_in_transformers.ipynb) — Try sentiment analysis, zero-shot classification, text generation, fill-mask, named entity recognition, summarization, and speech recognition with the `transformers` pipeline API.

### Datasets and preprocessing
- [`using_datasets_library.ipynb`](notebooks/using_datasets_library.ipynb) — Load and explore the Drugs.com reviews dataset with 🤗 Datasets; clean and transform columns, then create train, validation, and test splits.
- [`creating_your_own_dataset.ipynb`](notebooks/creating_your_own_dataset.ipynb) — Fetch GitHub issues and comments, prepare them as a dataset, and work with the Hugging Face Hub.
- [`preprocessing_the_data.ipynb`](notebooks/preprocessing_the_data.ipynb) — Explore data preprocessing for model workflows.

### Fine-tuning models
- [`fine_tuning_using_trainer_api.ipynb`](notebooks/fine_tuning_using_trainer_api.ipynb) — Fine-tune BERT for the GLUE MRPC sentence-pair classification task using the Hugging Face `Trainer` API.
- [`fine_tuning_using_trainer_api_and_visualizing_weight&biases.ipynb`](notebooks/fine_tuning_using_trainer_api_and_visualizing_weight%26biases.ipynb) — Explore Trainer-based fine-tuning and experiment-tracking configuration with Weights & Biases.
- [`fine_tuning_using_trainer_api_push_to_hub.ipynb`](notebooks/fine_tuning_using_trainer_api_push_to_hub.ipynb) — Fine-tune on GLUE MRPC and configure the training workflow to push the model to the Hugging Face Hub.
- [`training_model_in_pytorch_without_trainer_class.ipynb`](notebooks/training_model_in_pytorch_without_trainer_class.ipynb) — Explore model training with PyTorch without using the `Trainer` class.

### Semantic search
- [`semantic_search_with_FAISS.ipynb`](notebooks/semantic_search_with_FAISS.ipynb) — Create embeddings from GitHub issue discussions and use FAISS to retrieve semantically similar examples.

## Getting Started

The notebooks are designed for experimentation and can be opened in a Jupyter environment or Google Colab. Some notebooks download datasets or pretrained models, and may require internet access and additional packages.

The repository includes a [`requirements.txt`](requirements.txt) file listing Python dependencies used in the project.

## Learning Goals

- Use pretrained models for common NLP and machine-learning tasks.
- Understand dataset loading, cleaning, transformation, and tokenization.
- Fine-tune pretrained models with the Hugging Face `Trainer` API and with PyTorch.
- Evaluate model predictions and explore experiment tracking.
- Generate embeddings and perform semantic search with FAISS.
- Learn by building and iterating through practical notebook examples.
