# NLTK Chatbot

This project is an **NLTK-based chatbot** that can answer questions from a given text data file. It uses Natural Language Processing (NLP) techniques to understand and respond to user inputs in a conversational manner.

## Features

- Responds to user queries based on pre-loaded textual data.
- Uses **TF-IDF Vectorization** and **Cosine Similarity** for retrieving relevant responses.
- Basic **greeting function** to enhance conversational flow.
- Implements NLP techniques such as **tokenization**, **lemmatization**, and **punctuation removal** for better query understanding.

## Tech Stack

- **Programming Language:** Python
- **Libraries:** NLTK, NumPy, Scikit-learn
- **Tools:** Google Colab, Jupyter Notebooks

## How It Works

1. The chatbot reads a text file containing information (in this case, about the Ganga River).
2. When the user inputs a query, the chatbot processes the input using NLP techniques.
3. It calculates **TF-IDF** for the input query and compares it to the corpus using **cosine similarity** to find the best matching response.
4. If a matching sentence is found, it returns the most relevant response from the text. Otherwise, it apologizes for not understanding the input.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/nltk-chatbot.git
    cd nltk-chatbot
    ```

2. Install the required dependencies:
    ```bash
    pip install nltk numpy scikit-learn
    ```

3. Download the necessary NLTK resources:
    ```python
    import nltk
    nltk.download('punkt')
    nltk.download('wordnet')
    ```

4. Run the Python script:
    ```bash
    python chatbot.py
    ```

## Usage

1. Start the chatbot and interact by asking questions related to the content in the text file.
2. Type "bye" to end the conversation.
3. You can update the chatbot’s data by modifying the text file loaded into the script.

## Example

```plaintext
User: Hello
Bot: Hey there!

User: Tell me about the Ganga River.
Bot: The history of the Ganga River, also known as the Ganges, is deeply intertwined with the cultural, spiritual, and environmental heritage of India...
```

## Contribution

Feel free to fork the repository, open issues, or submit pull requests if you would like to contribute to this project.

## License

This project is licensed under the MIT License.
