# AMC AI Assistant Dataset

A simple Python interface for interacting with OpenAI's Assistant API. This project provides a command-line chat interface that allows users to communicate with an OpenAI Assistant.
Containing both AMC exam preparation datasets and pre-processed vector embeddings, paired with GPT-4o fine-tuning implementations, enabling medical students to leverage vectorized question banks and domain-specific language models for enhanced exam preparation.


### OpenAI Setup

1. Create an OpenAI account and obtain an API key from [OpenAI Platform](https://platform.openai.com/)
2. Create a fine-tuning job with the following parameters:
   - Epochs: 3
   - Learning rate multiplier: 2
   - Batch size: 1

### Vector Store Creation
1. Download the provided vectore data and upload on the OpenAI plaftform to create a vector store storage
2. This will be used to enhance the assistant's response capabilities according to the AMC guideline.

### Assistant Configuration
1. Create a new assistant
2. Select the fine-tuned model
3. Connect the vector storage
4. Save the assistant ID

## Usage
1. Get assistance with:
   - AMC related concepts
   - Exam preparation design
   - Exam question
   - Implementation guidance
2. Exit by typing 'quit', 'exit', or 'bye'



