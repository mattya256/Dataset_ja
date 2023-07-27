# Dataset_ja

https://huggingface.co/datasets/Dahoas/synthetic-instruct-gptj-pairwise
上の英語データを日本語に翻訳したものです。pandasとDatsetの両方で一応保存しています。
pdで読み込む際は
pd.read_csv(ファイル名, quotechar='"', usecols=[0, 1, 2, 3, 4, 5])
で読み込めると思います。
