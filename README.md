# COSE_474_GNN_Project
- By Hanjin Choi, Wesley Bailey, Joo Hwan Yeon, Dong Hwan Kim.

To check our main project details, go take a look at GNN.pdf!

In data preprocessing part_sentiment you might need...

- pip install transformers

In sentiment, I used pretrained transformer model to gain sentiment scores driven from the text reviews.
Since I let that args as default, transformers pipeline will take distil BERT_based finetuned model.

Data preprocessing GNN,

I wasn't able to find the data set that includes all the text review, ratings, and categories etc.. 
So I just build one!

By concatanating with other dataset that includes, categories, ad_methods, time of accesses.
Finally we now have 414,805 features of medium sized dataset for our GNN GCMC model. 
