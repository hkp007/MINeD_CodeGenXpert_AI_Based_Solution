# MINeD_CodeGenXpert_AI_Based_Solution

# CodeGenXpert: Llama2 Fine-tuning with Custom Dataset Using PEFT and 4-Quantization



## Description:
This project aims to fine-tune the Llama2 model using a custom dataset. The custom dataset is created by us using superficially designed framwork and generating descriptions for these code snippets using ChatGPT. The dataset is then labeled and converted to specific format and then utilized to fine-tune the Llama2 model by using parameter efficient fine tuning and 4- bit quantization.


## Features:
Fine-tuning Llama2 with a custom dataset
Dataset creation from by Manual way .
Description generation for code snippets using ChatGPT
Use of parameter efficient fine -tuning
User input text for code specification generation


## Requirements:
Python 3.x
TensorFlow
Hugging Face Transformers Library
Pandas
NumPy

## Install dependencies:

!pip install -q -U transformers datasets accelerate peft trl bitsandbytes wandb


## Usage:

# Dataset Creation:

We decided specific snippets and architechture that the company shall follow and generated code and input text combination according to that.Then we converted it in required format that llama 2 can train on efficiently.


## Fine-tuning Llama2:

Load the custom dataset.
Set parameters for 4-bit quantization and PEFT
Fine-tune the Llama2 model using the dataset.
Save the fine-tuned model weights.


## Generating Code:

User inputs text specifying code requirements.
Utilize the fine-tuned Llama2 model to generate code snippets based on the input text.
