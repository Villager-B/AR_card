# AR_CARD 

AR.jsでAR名刺を作るレポジトリ

## QR Code Generated

Pythonのライブラリ`CuteR`を使用して画像をベースにサクッとQR Codeを作成する．

内容はリポジトリのGitHub Pagesのリンクを与える．

### Install

```
pip install CuteR
```

### Useage

```
# Color画像生成
CuteR -C -o sample_output.png sample_input.png http://www.example.com
```

私の場合は以下のようになる．

```
CuteR -C -o ./img/qr_profile.png ./img/profile.jpg https://villager-b.github.io/AR_card/
```

## AR Marker Create

AR.js用のAR Markerを作成する．

[AR.js Marker Training](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html)

`UPLOAD`から先程作成したQR Codeの画像を選択する．

後はMARKER，IMAGEをダウンロードする．