# NLP-MachineTranslation
## Objective
To build a deep neural network that functions as part of an end-to-end machine translation pipeline. The completed pipeline will accept English text as input and return the French translation.

# Requirements
This project requires GPU acceleration to run efficiently. 

# Install
- Python 3
- NumPy
- TensorFlow
- Keras

# Translation
English Text = 'he saw a old yellow truck'
French Text(Translated)        = 'il a vu un vieux camion jaune'
French Text(Google Translator) = 'il a vu un vieux camion jaune'

# Result
Ran 25 epochs and achieved 98% accuracy at 11th epoch with 463us/step time consumed per epoch

# Building the Pipeline
Below is a summary of the various preprocessing and modeling steps. The high-level steps include:

Preprocessing: Load sentences, cleaning, tokenization, padding.
Modeling: Build the RNN model, train, and testing. 
Prediction: Translate English to French, and compare the output translations to what it is supposed to be.
Iteration: iterate on the model, experimenting with different architectures

# Preprocessing
Cleaning - 
Tokenization - 
Padding - 

# Modeling
4 RNN Models
  - Simple RNN
  - Embedding layers implemented
  - Bidirectional layers implemented
  - Encoder-Decoder model
  - (Final model) Combination of layers for higher accuracy
