# GPT-1
## Reimplemented GPT1 following the paper "Attention is all you need" Build/Pre-trained Transformer architecture used in GPT1 from scratch. The pretraining included writing mathematical expressions and codes of different parts of transformer architecture.

![transformer_arch](https://github.com/diyamth/GPT-1/assets/94824519/948b2f48-b86c-4771-b0a3-11ac2b4fb417)

## Features 
- **Transformer Architecture** - Encoder-Decoder Structure, Self-Attention Mechanism, Multi-Head Attention, Positional Encoding
- **Model Components** - Layer Normalization, Feed-Forward Networks, Residual Connections, Dropout
- **Training and Optimization** - Custom Training Loop and Loss Function: Used cross-entropy loss to train the language model to predict the next token in the sequence. Developed a custom training loop to handle data loading, forward and backward passes, and parameter updates.

## Dataset 
The model is trained on all seven parts of the Harry Potter novels. 

## Training and Evaluation 
The model was trained on RTX 3060 12GB NVIDIA GPU
 + Training loss - 1.05
 + Validating loss - 1.13
 + No of iterations - 10,000

It was tested as it completed the sentence the user gave through the prompt.

## Getting Started 
1. Clone the repository: https://github.com/diyamth/GPT-1.git
2. Install required libraries: pip install -r requirements.txt

## License 
This project is under MIT LICENSE

