# Documentation Chat with Search

This project is a Streamlit application that provides an interactive chat interface for users to ask questions about Generative AI and other topics. It leverages the [Langchain](https://github.com/langchain-ai/langchain) framework to integrate various search tools and APIs, including [Arxiv](https://arxiv.org/), [Wikipedia](https://www.wikipedia.org/), and [DuckDuckGo](https://duckduckgo.com/), to provide comprehensive answers.

## Features

- **Interactive Chat Interface**: Users can input questions and receive responses in a chat format.
- **Multiple Data Sources**: The application uses Arxiv, Wikipedia, and DuckDuckGo to fetch relevant information.
- **Real-time Streaming**: Responses are generated in real-time using the ChatGroq model.
- **Session Management**: Maintains the context of the conversation using [Streamlit's](https://docs.streamlit.io/library/api-reference) session state.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/shrchrds/Documentation-Chat-with-Search.git
   cd Documentation-Chat-with-Search
    ```
2. Set up a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
3. Install the required packages:

```bash 
pip install -r requirements.txt```

4. Set up environment variables:
    - Create a .env file in the root directory.
    - Add your GROQ API key:

```bash GROQ_API_KEY=your_groq_api_key_here ```

5. Usage

    1. Run the Streamlit app:
```bash streamlit run app.py```    
    2. Interact with the chat interface:Enter your questions in the chat input box.The assistant will provide answers using the integrated search tools.
