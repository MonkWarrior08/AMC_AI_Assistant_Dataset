
A simple Python interface for interacting with OpenAI's Assistant API. This project provides a command-line chat interface that allows users to communicate with an OpenAI Assistant.
Containing both AMC exam preparation datasets and pre-processed vector embeddings, paired with GPT-4o fine-tuning implementations, enabling medical students to leverage vectorized question banks and domain-specific language models for enhanced exam preparation.

# AMC AI Assistant

An AI assistant powered by OpenAI's API, specifically fine-tuned for AMC-related interactions.

## Setup Instructions

### 1. Fine-tuning Setup
1. Create an OpenAI account and obtain an API key from [OpenAI Platform](https://platform.openai.com/)
2. Create a fine-tuning job on the OpenAI website using the provided JSONL file with the following parameters:
   - Epochs: 3
   - Learning rate multiplier: 2
   - Batch size: 1

### 2. Vector Store Creation
1. Upload your knowledge base to create a vector store storage
2. This will be used to enhance the assistant's response capabilities

### 3. Assistant Creation
1. Go to the [OpenAI Platform](https://platform.openai.com/)
2. Create a new assistant
3. Select the fine-tuned model created for AMC
4. Connect the vector storage to the assistant
5. Save the assistant ID for later use

### 4. Environment Setup
1. Clone this repository:
```bash
git clone [repository-url]
```

2. Install required dependencies:
```bash
pip install openai python-dotenv
```

3. Create a `.env` file in the project root with your OpenAI API key:
```
OPENAI_API_KEY=your-api-key-here
```

### 5. Running the Application
1. Open `main.py`
2. Replace the empty `assistant_id` variable with your assistant ID
3. Run the application:
```bash
python main.py
```

## Usage
- Type your message and press Enter to interact with the assistant
- Type 'quit', 'exit', or 'bye' to end the conversation

## Important Notes
- Ensure your OpenAI API key has sufficient credits
- Keep your API key and assistant ID secure
- The fine-tuning process may take some time to complete

## License
This project is licensed under the MIT License - see the LICENSE file for details.
