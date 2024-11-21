
A simple Python interface for interacting with OpenAI's Assistant API. This project provides a command-line chat interface that allows users to communicate with an OpenAI Assistant.
Containing both AMC exam preparation datasets and pre-processed vector embeddings, paired with GPT-4o fine-tuning implementations, enabling medical students to leverage vectorized question banks and domain-specific language models for enhanced exam preparation.

## Key Aspects:

1. **Data Preparation**
   - Clean, high-quality training data
   - Consistent format (prompt-completion pairs)
   - Relevant to your specific use case

2. **Fine-tuning Process**
   - Uses supervised learning
   - Requires significantly less data than full model training
   - Typically needs hundreds to thousands of examples

3. **Benefits**
   - Better performance on specific tasks
   - More consistent outputs
   - Reduced need for detailed prompting

## Vector Storage

Vector storage is a method of storing and retrieving text or other data as mathematical vectors, making it efficient to find similar items.

1. **Embeddings**
   - Text converted to numerical vectors
   - Captures semantic meaning
   - Usually high-dimensional (e.g., 1536 dimensions for OpenAI embeddings)


## Features

- Real-time chat interaction with OpenAI Assistant
- Environment variable configuration for API keys
- Thread management for conversations
- Simple command-line interface
- Graceful exit handling

## Prerequisites

Before running this project, you'll need:

- Python 3.6 or higher
- An OpenAI API key
- An OpenAI Assistant ID

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/AMC_Assistant_ExamPrep.git
cd AMC_Assistant_ExamPrep
```
2. Install required dependencies:
```bash
pip install openai python-dotenv
```
3. Create a .env file in the project root and add your OpenAI API key:
```bash
OPENAI_API_KEY=your_api_key_here
```
## Configuration
1. Replace the assistant_id in the main() function with your OpenAI Assistant ID:
```bash
assistant_id = "your_assistant_id_here"
```
## Usage
1. Run the script:
```bash
python main.py
```
To exit the chat, type any of the following commands:

'quit'
'exit'
'bye'

## License
This project is licensed under the MIT License - see the LICENSE file for details.
