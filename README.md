# Finetuning GPT2-large with 8 bit optimizer

A demo of finetuning GPT2-large using 8-bit optimizer from bitsandbytes library.

## How to run
1. Download the notebook
2. Upload it to your Kaggle account
3. Pick GPU accelerator (it should give you a Tesla-P100 with 16 Gb VRAM)
4. Run the notebook

## Takeaway
TLDR &mdash; 8-bit optimizer reduces memory footprint from 14 Gb to 9.7 Gb, 
allowing, for example, training the model in Google colaboratory on Tesla K80.