# AMC AI Assistant

A simple Python interface for interacting with OpenAI's Assistant API. This project provides a command-line chat interface that allows users to communicate with an OpenAI Assistant.
Containing both AMC exam preparation datasets and pre-processed vector embeddings, paired with GPT-4o fine-tuning implementations, enabling medical students to leverage vectorized question banks and domain-specific language models for enhanced exam preparation.


## Setup Instructions

### 1. Installation

1. Clone this repository:
```bash
git clone https://github.com/MonkWarrior08/AMC_Assistant_ExamPrep.git
cd AMC_Assistant_ExamPrep
```

2. Install dependencies using the requirements file:
```bash
pip install -r requirements.txt
```

### 2. Environment Configuration

1. Create a `.env` file in the project root:
```bash
touch .env  # macOS/Linux
# or manually create .env file in Windows
```

2. Add your OpenAI API key to the `.env` file:
```
OPENAI_API_KEY=your-api-key-here
```

### 3. OpenAI Setup

1. Create an OpenAI account and obtain an API key from [OpenAI Platform](https://platform.openai.com/)
2. Create a fine-tuning job with the following parameters:
   - Epochs: 3
   - Learning rate multiplier: 2
   - Batch size: 1

### 2. Vector Store Creation
1. Download the provided vectore data and upload on the OpenAI plaftform to create a vector store storage
2. This will be used to enhance the assistant's response capabilities according to the AMC guideline.

### 3. Assistant Configuration
1. Create a new assistant
2. Select the fine-tuned model
3. Connect the vector storage
4. Save the assistant ID

### 4. Application Setup
1. Open `main.py`
2. Replace the empty `assistant_id` variable with your assistant ID
3. Run the application:
```bash
python main.py
```
## Usage
1. Get assistance with:
- AMC related concepts
- Exam preparation design
- Exam question
- Implementation guidance
2. Exit by typing 'quit', 'exit', or 'bye'



