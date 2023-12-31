# GPT Rocket 🚀
 
GPT Rocket is a VS Code extension that leverages the power of OpenAI's GPT to provide AI-powered coding assistance. You can use it to create or refactor your code.

## Features

- `vs-gpt-rocket.sendSelectionToChatGPT` command: This command sends the selected text in the editor to ChatGPT, gets a response, and replaces the selected text with the response from ChatGPT.

## Usage

1. Install the extension in VS Code.
2. Configure your OpenAI API key and rules in the settings (File > Preferences > Settings).
3. Select some text in your editor.
4. Run the command `vs-gpt-rocket.sendSelectionToChatGPT` from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

## Configuration

You can configure the extension via the following settings:

- `vs-gpt-rocket.apiKey`: The API key for OpenAI. It's a string value and it's mandatory.
- `vs-gpt-rocket.rules`: The rules for the AI model. It's a multiline string, you can enter it as an array of strings where each string represents a line. It's also mandatory.

To set these values, go to your settings (`File > Preferences > Settings` or `Code > Preferences > Settings` on Mac), search for "GPT Rocket", and enter your desired values.

## Requirements

This extension requires an OpenAI API key to work. You can get this key by subscribing to the OpenAI API.

## Known Issues

Currently, there are no known issues. If you encounter any issues, please report them in the issue tracker.

## Release Notes

### 1.0.0

Initial release

### For more information

For more information about OpenAI and the GPT-4 model, you can visit the official [OpenAI website](https://openai.com/).

**Enjoy!**
