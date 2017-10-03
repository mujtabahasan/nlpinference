# Natural Language Inference using LSTM based encoding

## Dependencies

* Python 2.7
* Theano 0.8.2

## Running the Script
1. Download and preprocess 
```
cd data
bash fetch_and_preprocess.sh
```

2. Train and test model
```
cd scripts
bash train.sh
```

The result is in `log.txt` file.
