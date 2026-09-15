# 最小PWA

## 起動

このフォルダで次を実行します。

```bash
python -m http.server 8000
```

Windowsで `python` が見つからない場合は、次を試します。

```powershell
py -m http.server 8000
```

その後、ChromeまたはEdgeで `http://localhost:8000` を開きます。

## 確認

1. ページを開いてから一度再読み込みします。
2. ブラウザの開発者ツールでネットワークをオフラインにします。
3. もう一度再読み込みし、画面が表示されれば成功です。
4. ブラウザのインストール操作からPWAとして追加できます。


# デプロイ

```
firebase deploy --only hosting
```