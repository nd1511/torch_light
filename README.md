<p align="center"><img width="40%" src="pytorch_logo.png" /></p>

--------------------------------------------------------------------------------

This repository includes basics and advanced examples for deep learning by using [Pytorch](http://pytorch.org/).
<br/>
Basics which are basic nns like Logistic, CNN, RNN, LSTM are implemented with few lines of code, advanced examples are implemented by complex model.
<br/>
It is better finish [Official Pytorch Tutorial](http://pytorch.org/tutorials/index.html) before this.

##### Continue updating...

## Tutorial
Get tutorial series in [Zhuanlan](https://zhuanlan.zhihu.com/c_135985394) if know Chinese

## Tabel of Pytorch Examples

#### 1. Basics

* [Cbow](https://github.com/ne7ermore/torch_light/tree/master/cbow)
* [N-Gram](https://github.com/ne7ermore/torch_light/tree/master/ngram)
* [CNN Text classfication](https://github.com/ne7ermore/torch_light/tree/master/cnn-text-classfication)
* [LSTM Text classfication](https://github.com/ne7ermore/torch_light/tree/master/lstm-text-classfication)

#### 2. Reinforcement Training
* [AlphaGo-Zero](https://github.com/ne7ermore/torch_light/tree/master/alpha-zero)
* [Image-Cap](https://github.com/ne7ermore/torch_light/tree/master/Image-Cap)
* [Reinforced Translate](https://github.com/ne7ermore/torch_light/tree/master/reinforced-translate)
* [Toy](https://github.com/ne7ermore/torch_light/tree/master/gym)

#### 3. NLP
* [Poetry VAE-NLG](https://github.com/ne7ermore/torch_light/tree/master/vae-nlg)
* [Seq2seq](https://github.com/ne7ermore/torch_light/tree/master/seq2seq)
* [BiLSTM CRF NER](https://github.com/ne7ermore/torch_light/tree/master/biLSTM-CRF)
* [LSTM CNNs CRF](https://github.com/ne7ermore/torch_light/tree/master/LSTM-CNNs-CRF)
* [Chinese Poetry NLG](https://github.com/ne7ermore/torch_light/tree/master/ch-poetry-nlg)
* [BiMPM](https://github.com/ne7ermore/torch_light/tree/master/biMPM)
* [Pair Ranking Cnn](https://github.com/ne7ermore/torch_light/tree/master/pair-ranking-cnn)
* [BiLSTM CRF](https://github.com/ne7ermore/torch_light/tree/master/biLSTM-CRF-cut)
* [Capsule Text classfication](https://github.com/ne7ermore/torch_light/tree/master/capsule-classfication)
* [Retrieval Based Chatbots](https://github.com/ne7ermore/torch_light/tree/master/retrieval-based-chatbots)
* [Hierarchical for Summarization and Classification](https://github.com/ne7ermore/torch_light/tree/master/hierarchical-sc)

#### 4. Vision
* [DenseNet](https://github.com/ne7ermore/torch_light/tree/master/DenseNet)
* [Neural Style](https://github.com/ne7ermore/torch_light/tree/master/neural-artistic-style)
* [DC Gan](https://github.com/ne7ermore/torch_light/tree/master/dc-gan)
* [Facial Beauty Prediction](https://github.com/ne7ermore/torch_light/tree/master/facial-beauty-prediction)

#### 5. Special Things
* [Customize](https://github.com/ne7ermore/torch_light/tree/master/Customize)

## Getting Started

### clone code
```
$ git clone git@github.com:ne7ermore/torch_light.git
```
### train

```
$ cd torch_light/project
$ python3 main.py
```

or

```
$ cd torch_light/project
$ python3 corpus.py
$ python3 main.py
```

or

```
$ cd torch_light/project
$ python3 corpus.py
$ python3 train.py
```

## Citation
If you find this code useful for your research, please cite:
```
@misc{TaoTorchLight,
  author = {Ne7ermore Tao},
  title = {torch_light},
  publisher = {GitHub},
  year = {2018},
  howpublished = {\url{https://github.com/ne7ermore/torch_light}}
}
```

## Contact
Feel free to contact me if there is any question (Tao liaoyuanhuo1987@gmail.com).
Tao Ne7ermore/ [@ne7ermore](https://github.com/ne7ermore)

## Dependencies
* [Python 3.5](https://www.python.org)
* [PyTorch 0.2.0](http://pytorch.org/)
* [Numpy 1.13.1](http://www.numpy.org/)
