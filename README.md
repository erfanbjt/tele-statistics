# Telegram Statistics
Export statistics for a telegram group chat

## How to run
First, in your main repo directory, run the following code to add `src` to your `PYTHONPATH`:
```
export PYTHONPATH=${PWD}
```

Then run:
```
python src/chat_statistics/stats.py
```
to generate a word cloud of json data in `DATA_DIR`
