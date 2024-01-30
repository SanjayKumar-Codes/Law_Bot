
# Industrial Mining Law Bot

Welcome to the Industrial Mining Law Bot repository! This project provides a chatbot designed to assist with legal inquiries related to industrial mining. The chatbot is built using PyTorch for neural network modeling, NLTK for natural language processing, and is trained on a dataset of intents specific to industrial mining laws.

## Overview

The Industrial Mining Law Bot is designed to answer legal questions and provide information related to industrial mining regulations and compliance. It uses a neural network model to understand user input and generate responses based on the provided dataset of intents.

## Requirements

- Python 3.x
- PyTorch
- NLTK
- Other dependencies (specified in `requirements.txt`)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/imonishkumar/law-bot.git
   cd industrial-mining-law-bot
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Download NLTK data:**

   ```bash
   python -m nltk.downloader punkt
   ```

4. **Train the model:**

   ```bash
   python train.py
   ```

   This step will generate a `data.pth` file containing the trained model parameters and other necessary information.

## Usage

Run the Industrial Mining Law Bot interactively:

```bash
python chat.py
```

The chatbot will prompt you to type a legal question related to industrial mining, and it will respond based on the trained model.

Type "quit" to exit the chat.

## Customization

- You can modify the intents in the `intents.json` file to tailor the chatbot's responses to specific industrial mining legal topics.
- Experiment with different hyperparameters in the `train.py` script to enhance the model's performance.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the legal and mining communities for their insights and contributions.

Feel free to contribute, open issues, or suggest improvements! For legal advice, always consult with a qualified professional.
