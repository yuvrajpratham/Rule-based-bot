# Simple Rule-Based Chatbot README

## Overview

This project is a simple rule-based chatbot that engages in conversation based on predefined rules and patterns. The chatbot interacts with users, asks random questions, and responds according to specific intents defined in the code.

## Requirements

To run this project, you will need:

- Python 3.x
- Required library: `re`

You can install the necessary library using pip:

```bash
pip install regex
```

## Usage

1. Clone this repository to your local machine.

```bash
git clone <repository_url>
```

2. Navigate to the project directory.

```bash
cd <project_directory>
```

3. Run the main script to start the chatbot.

```bash
python chatbot.py
```

## Implementation Details

### Rule-Based Approach

The chatbot utilizes a rule-based approach to understand and respond to user input. It defines patterns using regular expressions (imported from the `re` module) to match specific intents such as describing planets, answering questions, or providing information about certain topics.

### Conversation Flow

- The chatbot begins by greeting the user and asking for their name.
- It then randomly selects a question from a predefined list and prompts the user to respond.
- Based on the user's input, the chatbot matches the reply to predefined intents using regular expressions.
- If a match is found, the chatbot responds accordingly with a predefined response.
- If no match is found, the chatbot prompts the user for more information or provides a generic response.

## File Structure

- `chatbot.py`: Main script containing the chatbot implementation.
- `README.md`: This file providing an overview of the project.

## Contributors

- [Khan Juned](https://github.com/junedkhan9310) - Project Developer
