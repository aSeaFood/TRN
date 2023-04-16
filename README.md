# Few-shot Relation Extraction with Automatically Generated Prompts

This is an implemetation of the paper "Few-shot Relation Extraction with Automatically Generated Prompts".

## Requirements
All requirements for PET can be found in **requirements.txt**. You can install all required packages with `pip install -r requirements.txt`.

## How the code is executed

Example:
```
python train_trn.py --trainN 5 --N 5 --K 1 --Q 1 --model TRN --encoder bert --hidden_size 768 --val_step 1000 --batch_size 8
```
--trainN: N in train 
--N –K: N-way-K-shot
--Q: Num of query per class
--model: model name, TRN
