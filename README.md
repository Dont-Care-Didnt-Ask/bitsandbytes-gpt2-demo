# Finetuning GPT2-large with 8 bit optimizer

A demo of finetuning GPT2-large using 8-bit optimizer from bitsandbytes library.
Run on Tesla-P100 with 16 Gb of VRAM in Kaggle.

TLDR --- 8-bit optimizer reduces memory footprint from 14 Gb to 9.7 Gb, 
allowing, for example, training the model in Google colaboratory on Tesla K80.