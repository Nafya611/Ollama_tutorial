# OllamaTutorial

This project demonstrates how to use [Ollama](https://ollama.com/) to run and interact with custom language models locally. In this example, we interact with a Jon Snow character model, simulating a conversation with the Lord Commander of the Night's Watch from Game of Thrones.

## Features
- Run local LLMs using Ollama
- Simulate character-based conversations (e.g., Jon Snow)
- Example prompts and responses

## Example Conversation
Below is a sample interaction with the Jon Snow model using Ollama:

![Start conversation with Jon Snow](attachments/image1.png)

![Jon Snow on power](attachments/image2.png)

![Jon Snow farewell](attachments/image3.png)

## Usage
1. Install [Ollama](https://ollama.com/)
2. Download or create a model (e.g., `jon_snow`)
3. Run the model in your terminal:
   ```powershell
   ollama run jon_snow
   ```
4. Start chatting with the character!

## Files
- `Modelfile`: Model configuration for Ollama
- `package.py`: Python utilities (if any)
- `sample_request.py`: Example script to interact with the model programmatically

## License
This project is for educational and demonstration purposes.
