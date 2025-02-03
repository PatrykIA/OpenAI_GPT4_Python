# OpenAI Chat Bot

A simple Python chatbot that uses OpenAI's API to interact with GPT models.

## Requirements

- Python 3.8 or newer
- OpenAI API key

## Installation

1. Clone the repository:

git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
cd REPO_NAME


2. Install required dependencies:

pip install -r requirements.txt


3. Configure environment variables:
   - Copy `.env.example` to `.env`
   - Open `.env` file and enter your OpenAI API key

## Environment Variables

Create a `.env` file in the root directory with the following variable:

OPENAI_API_KEY=your_api_key_here


## Usage

Run the application using:

python main.py


The chatbot will:
1. Start a conversation
2. Accept user input
3. Generate responses using GPT-4
4. Continue until you type 'quit', 'exit', or 'bye'

## Project Structure

├── main.py # Main application file
├── .env # Environment variables (not tracked in git)
├── .env.example # Example environment variables
├── .gitignore # Git ignore file
├── README.md # This file
└── requirements.txt # Project dependencies


## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Patryk Rogowski

## Acknowledgments

- OpenAI for providing the GPT API
