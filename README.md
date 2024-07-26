# LangChain RAG App with OpenAI

## Description

This Python script demonstrates a Retrieval-Augmented Generation (RAG) application built using LangChain and OpenAI's API. It leverages OpenAI's language models (LLMs) to generate responses based on content from Markdown files.

**NOTE:** This application is not a conversational chatbot.

## Instructions

1. Run this command to install the required dependecies:

    ```
    pip install -r requirements.txt
    ```

2. Run this command to install markdown dependencies:

    ```
    pip install "unstructured[md]"
    ```

3. Create a ```.env``` file and put your OpenAI api key like this:
    ```
    OPENAI_API_KEY=your_api_key
    ```

## Resources

- LangChain RAG Tutorial: [https://python.langchain.com/v0.2/docs/tutorials/rag/#detailed-walkthrough](https://python.langchain.com/v0.2/docs/tutorials/rag/#detailed-walkthrough)
- LangChain Markdown Document Loader Documentation: [https://python.langchain.com/v0.2/docs/how_to/document_loader_markdown/](https://python.langchain.com/v0.2/docs/how_to/document_loader_markdown/)
- RAG + Langchain Python Project: Easy AI/Chat For Your Docs Youtube Video: [https://www.youtube.com/watch?v=tcqEUSNCn8I&t=252s](https://www.youtube.com/watch?v=tcqEUSNCn8I&t=252s)