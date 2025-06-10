# Youtube_Downloader

## howto

- プログラム実行には`pytube==15.0.0：pydub==0.25.1` が必要です。
- pythonのバージョンを整えてのライブラリインストール含めローカル環境構築が煩雑になるため以下の手順で環境を構築します。

```
# ステップ1：仮想環境を構築・有効化

python3 -m venv venv
source venv/bin/activate


# ステップ2：依存ライブラリをインストール
pip install -r requirements.txt

# 上で入らない場合は以下（python/pipのpathをvenvに向けてインストール）
python -m pip install yt_dlp

# ステップ3：スクリプトを実行

python 1or2.py
ダウンロードしたいYouTubeのURLを入力してください: 
ダウンロードモードを選択してください [1:動画, 2:音声(MP3)] :
```

