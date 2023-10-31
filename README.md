# Auto Code - NLP text prediction
Auto code is a NLP model that can predict python code snippets with the provided code to it. It is a LSTM (Long Short Term Memory model) with word Embedding.

It is trained with 606 rows of code snippets on a Macbook M1 Pro with a Total embedding word size of 237. The major thing I have tried in the project is to make the tokenizer of TensorFlow detect Special characters.

Special characters are converted to texts and then are tokenized and is reversed back to symbols after prediction.

## Modules to install

```bash
python3 -m pip install TensorFlow

pip install pandas

pip install numpy

pip install matplotlib
```

#### Frameworks and Languages used
* Tensorflow
* Pandas
* Numpy
* Matlab

#### Training with more data:
To train the model with more data just add more code snippets in each cell of [dataset.csv](https://github.com/enockjamin01/autocode/blob/main/dataset.csv) or add more data as python list in [dataprocessing.ipynb](https://github.com/enockjamin01/autocode/blob/main/dataprocessing.ipynb) file and run code to append data to [csv](https://github.com/enockjamin01/autocode/blob/main/dataset.csv) file

## Splitting of data

* Train = .8
* Validiation = .2

## Accuracy and Loss plot

* Accuracy

![Accuracy](https://github.com/enockjamin01/autocode/blob/main/plots/accuracy.png)

* Loss

![Loss](https://github.com/enockjamin01/autocode/blob/main/plots/loss.png)

## License

[MIT](https://github.com/enockjamin01/autocode/blob/main/LICENSE)
