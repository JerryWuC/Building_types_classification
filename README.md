# Building_types_classification
Aim: Using for classifying building types

Envirment:
python 3.6.4
pytorch 1.1

Dataset:
===
The data directory: THUCNews\data
There are five textfiles:
class.txt: label set, including 13 labels divided by the paper
dev.txt: development set
pred.txt: prediction set
test.txt: test set
train.txt: training set

Pre-train model:
the download link：https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-chinese.tar.gz
unzip the dolnloading file and put all the files under the directory: bert_pretrain

Usage: 
After installed all the needed modules and pre-train model, run this sentence to start training:
python run_train.py --model bert_CNN

As for predition, 
python run_pred.py --model bert_CNN
