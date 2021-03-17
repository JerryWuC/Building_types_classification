# Building_types_classification
Aim: Using for classifying building types

Envirment:
python 3.6.4
pytorch 1.1

Dataset:
The data directory: THUCNews\data
There are five textfiles:
class.txt: label set, including 13 labels divided by the paper
dev.txt: development set
pred.txt: prediction set
test.txt: test set
train.txt: training set

Pre-train model:
the download link：https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-chinese.tar.gz
After unzipping do not need to change, directly into 解压后不需改动，直接放到bert_pretrain文件夹下

Usage: 
After installed all the needed modules and pre-train model, run this sentence to start training:
python run.py --model bert_CNN

As for predition, 
