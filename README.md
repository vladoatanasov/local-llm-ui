# Local LLM UI

Local LLM UI is a Flask application that provides a simple web interface for interacting with the LLaMA model.

## Requirements

* Python 3.12+
* Flask 3.1.0
* langchain_ollama 0.2.0
* ollama 0.3.3

## Installation

1. Clone the repository: `git clone https://github.com/doaonduty/LocalLLMUI.git`
2. Make sure you have venv setup to keep things clean and isolated.
3. Install dependencies: `pip install -r requirements.txt`
4. Run the application: `python local_llm_ui.py`

## Usage

1. Open a web browser and navigate to `http://localhost:5000`
2. Enter a question or prompt in the input field and click the "Send" button
3. View the model's response in the conversation area

## API Documentation

The application provides a single endpoint:

* `/chat`: Handles POST requests with a JSON payload containing the user's input
* `curl -X POST -H "Content-Type: application/json" -d '{"message": "hello are you there?"}' http://127.0.0.1:5000/chat |jq`

## Contributing

Contributions are welcome! Please submit a pull request with your changes.
