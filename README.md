# Multi-Class-Text-Classification-with-Transformer-Models-
Classified textual data using BERT, RoBERTa and XLNET models by converting .csv datasets to .tsv format with HuggingFace library, and converting input examples into input features by tokenizing, truncating longer sequences, and padding long sequences.

**RoBERTa:** A Robustly Optimized BERT Pretraining Approach.

**XLNet:** Generalized Autoregressive Pretraining for Language Understanding
Analysed the architectures of these two models, study their training and
optimization techniques and finally use them to classify Human Emotions into
separate categories.

## Data Description
Emotion is a dataset of English Twitter messages with six basic emotions: anger, fear,
joy, love, sadness, and surprise. This dataset is taken from the hugging face library.
(https://huggingface.co/datasets/emotion)
The dataset comprises of three data categories,
- Train - 16000 rows and 2 columns
- Validation - 2000 rows and 2 columns
- Test - 2000 rows and 2 columns
The two columns are labels and text.
- 0: sadness
- 1: joy
- 2: love
- 3: anger
- 4: fear
- 5: surprise

## Aim
The project aims at building two models, namely RoBERTa and XLNet to perform
classification on the human emotion dataset.
Tech stack

**Language** - Python

**Libraries** - datasets, numpy, pandas, matplotlib, seaborn, ktrain, transformers,
tensorflow, sklearn

## Environment
- Jupyter Notebook

## Approach
- 1. Install the required libraries
- 2. Load the ‘emotion’ dataset
- 3. Read the dataset across all the three categories
- 4. Convert dataset object to data-frame and create a new feature
- 5. Data Visualization
     - Histogram plots
- 6. RoBERTa model
     - Create a RoBERTa model instance.
     - Split the train and validation data
     - Perform Data Pre-processing
     - Compile RoBERTa in a K-train learner object
     - Find optimal learning rate
     - Fine-tune the RoBERTa model on the dataset
     - Check for performance metrics
     - Save the RoBERTa model
     - Use the RoBERTa model on the test data and check for the
performance.
- 7. Understand the Autoregressive and Autoencoder models
- 8. XLNet model
     - Load the required libraries
     - Create an XLNet model instance
     - Split the train and validation data
     - Perform Data Pre-processing
     - Compile XLNet in a K-train learner object
     - Find optimal learning rate
     - Fine-tune the XLNet model on the dataset
     - Check for performance metrics
     - Save the XLNet model
     - Use the XLNet model on the test data and check for the performance
