# connect-to-zendesk-tutorial
This is the code for the tutorial [here](www.psychic.dev/post/how-to-connect-the-zendesk-api-to-langchain), showing how to connect articles from a Zendesk help center to LLMs using Psychic, Chroma, and LangChain.

## Running
1. Create an account at https://dashboard.psychic.dev/ (it's free) and connect a Zendesk account.
2. Rename `rename.env` to `.env` and fill in your own OPENAI_API_KEY and PSYCHIC_SECRET_KEY.
3. Replace `account_id` in `main.py` with the Account ID you used to connect to Zendesk in step 1.
4. [Install poetry](https://python-poetry.org/docs/) to run this project in a virtual environment.
5. Run the following in order:
    ```bash
    poetry install
    poetry shell
    python main.py
    ```