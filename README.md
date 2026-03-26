Crypto LLM Agent Trading Bot
How to build a trading bot for crypto with LLMs (not so great) and finbert (way better)

We use:

Create a virtual environment uv venv and activate it source .venv/bin/activate
Update your SERPER_API_KEY in the .env file
Install dependencies uv pip install -r pyproject.toml
Run whichever bot you want uv run 1. cryptobot_aggregate_sentiment-r1.py
NOTE: if you get a error that looks something like this, it's probs because the CCXT datastore isn't picking up the strategy returns, You can edit the ccxt datastore file to fix it. I gotta find the exact details on how to do this, but i'll update it in the next few days. lumibot/tools/ccxt_data_store.py
