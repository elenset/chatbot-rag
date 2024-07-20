# Chatbot-RAG

Chatbot-RAG is a Retrieval-Augmented Generation (RAG) chatbot that provides context-aware responses by leveraging a collection of Markdown files. It integrates several tools and libraries such as Lama.cpp, CTransformers, LangChain, Chroma, and Streamlit to enhance the chatbot experience.

## Features

- **Multi-chatbot Aggregation**: Environment for multiple chatbots targeting Q&A or daily conversation.
- **API Support**: Supports multiple APIs including HTTP, and Mass Platform.
- **Contextual Responses**: Uses Markdown files to provide context-based answers.
- **Memory Builder**: Loads Markdown pages, divides them into sections, calculates embeddings, and saves them for retrieval.
- **Streamlit Integration**: Interactive UI for better user experience.

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/elenset/chatbot-rag.git
    ```
2. **Navigate to the project directory:**
    ```sh
    cd chatbot-rag
    ```
3. **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

## Configuration

1. **Set your API key:**
    - Obtain an API key from the Tuling Robot website.
    - Set the API key in the `ChatBot.cfg` file.


## Usage

1. **Run the chatbot:**
    ```sh
    python main.py
    ```
2. **Access the Streamlit interface:**
    - Follow the instructions provided by the Streamlit server to access the interface in your web browser.

## Project Structure

- **`docs/`**: Contains the collection of Markdown files used for context.
- **`embeddings/`**: Stores the calculated embeddings for retrieval.
- **`scripts/`**: Contains scripts for various functionalities.
- **`ChatBot.cfg`**: Configuration file for setting API keys and tokens.
- **`requirements.txt`**: Lists the dependencies required for the project.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Additional Resources

For more information and examples on creating good `README.md` files, refer to the [GitHub guide on creating a README.md file](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-readmes).

---
By elenset
