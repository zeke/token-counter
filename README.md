# token counter

Python script for approximating token counts in JSON files. Uses Transformers.

Written by ChatGPT: https://chat.openai.com/share/0cadf000-ead2-483e-b338-a111f35f496f

## Usage

1. Put JSONL files in the `datasets` directory
2. `python token-counter.py`


## Example datasets

- [Hacker News](https://storage.googleapis.com/dan-scratch-public/fine-tuning/70k_samples.jsonl) -  all stories and comments from Hacker News from its launch in 2006 to present.
- [Elixir docstrings](https://raw.githubusercontent.com/cbh123/elixir_gen/main/outputs/docstrings.jsonl) - API reference documentation for all functions in the Elixir programming language’s standard library.
- [ABC notated music](https://storage.googleapis.com/andreas-scratch-public/massive_abcnotation_dataset.jsonl) - a collection of songs in a shorthand form of musical notation for computers.
- [Recipes](https://storage.googleapis.com/andreas-scratch-public/recipe-prompts.jsonl) - Lists of food ingredients as prompts, and recipe instructions as responses.
- [Bob Dylan Lyrics](https://gist.githubusercontent.com/cbh123/ad79e304d47aca1fe174eda70a2449c8/raw/fdca62f1f04b0eb104526469391606ba79026c34/dylan_title.jsonl) - Song titles and lyrics from Bob Dylan’s repertoire.
