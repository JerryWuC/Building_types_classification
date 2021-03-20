# Building_types_classification
    Using for classifying building types

Envirment:
==
python 3.6.4 <br>
pytorch 1.1

Dataset:
===
The data directory: `THUCNews\data` <br>
There are five textfiles: <br>
`class.txt`: label set, including 13 labels divided by the paper <br>
`dev.txt`: development set <br>
`pred.txt`: prediction set <br>
`test.txt`: test set <br>
`train.txt`: training set

Pre-train model:
==
the download link：https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-chinese.tar.gz <br>
unzip the downloading file and put all the files under the directory: `bert_pretrain`

Usage: 
==
After installed all the needed modules and pre-train model, run this sentence to start training: <br>
```
python run_train.py --model bert_CNN
```
As for prediction, run: <br>
```
python run_pred.py --model bert_CNN
```
