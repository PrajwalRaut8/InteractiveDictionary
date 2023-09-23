# Interactive Dictionary

Welcome to the Interactive Dictionary project! This Python-based interactive dictionary allows you to search for word meanings, find closely matching words for misspelled input, and access their meanings. It's a handy tool for enhancing your vocabulary and ensuring accurate word usage.

## Features

- **Word Search**: Simply enter the word you want to look up, and the dictionary will provide its meaning.

- **Typo Detection**: If you make a typo or enter a word not in the dictionary, the program will use the `get_close_matches` method to suggest closely matching words.

- **User Interaction**: If a closely matching word is found, the program will ask if it's the word you intended. You can respond with 'yes' or 'no.'

- **Meaning Display**: Once a word is correctly identified, the dictionary will display its meaning, enriching your understanding of the language.

## Getting Started

To use this interactive dictionary:

1. Clone this repository to your local machine.

2. Open a terminal and navigate to the project directory.

3. Run the `interactive_dictionary.py` script.

4. Follow the prompts to search for words and explore their meanings.

## Usage

Here's a brief example of how to use the Interactive Dictionary:

```bash
Enter a word: appl

Did you mean 'apple'? (Y/N): Y
Meaning of 'apple':
A round fruit with red, green, or yellow skin and crisp flesh.

Enter a word: serch
Did you mean 'search'? (Y/N): N
The word 'serch' does not exist in the dictionary.
