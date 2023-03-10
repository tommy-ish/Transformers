# transformers
Hugging Face Transformersを使ったnotebook

このリポジトリはHugging Face Transformersを使ったnotebookを集めたリポジトリです。このリポジトリのソースコードはHugging Faceのライブラリをできるだけ使って、簡単に書かれています。

## Hugging Face Transformersのインストール
Hugging Face Transformersは[ドキュメント](https://huggingface.co/docs/transformers/installation#install-with-pip)によると仮想環境にインストールするべきとされています。venvを使って.envという仮想環境を作るには
```console
$ python -m venv .env
```

仮想環境をアクティベート
```console
$ source .env/bin/activate
```

transformersをインストール
```console
$ pip install transformers
```

condaを使ってtransformersをインストールするには
```console
$ conda install -c huggingface transformers
```

次に[PyTorchのサイト](https://pytorch.org/get-started/locally/#start-locally)に従いPyTorchをインストールします。
