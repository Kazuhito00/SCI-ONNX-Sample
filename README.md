# SCI-ONNX-Sample
[SCI](https://github.com/tengyu1998/SCI)のPythonでのONNX推論サンプルです。<br>
ONNXに変換したモデルも同梱しています。変換自体を試したい方は[Convert2ONNX.ipynb](Convert2ONNX.ipynb)を使用ください。<br>

https://user-images.githubusercontent.com/37477845/164886829-7a2ad37c-8ba2-4085-904b-bd17ad8431b2.mp4

# Requirement 
* OpenCV 4.5.3.56 or later
* onnxruntime 1.8.0 or later
* Pytorch 1.8 or later ※ONNX変換を実施する場合のみ

# Demo
デモの実行方法は以下です。
```bash
python sample.py
```
* --device<br>
カメラデバイス番号の指定<br>
デフォルト：0
* --movie<br>
動画ファイルの指定 ※指定時はカメラデバイスより優先<br>
デフォルト：指定なし
* --model<br>
ロードするモデルの格納パス<br>
デフォルト：model/sci_512x512.onnx
* --input_shape<br>
モデルの入力サイズ<br>
デフォルト：512,512

# Reference
* [tengyu1998/SCI](https://github.com/tengyu1998/SCI)

# Author
高橋かずひと(https://twitter.com/KzhtTkhs)
 
# License 
SCI-ONNX-Sample is under [MIT License](LICENSE).

# License(Movie)
サンプル動画は[NHKクリエイティブ・ライブラリー](https://www.nhk.or.jp/archives/creative/)の[雨イメージ　夜の道路を走る車](https://www2.nhk.or.jp/archives/creative/material/view.cgi?m=D0002161702_00000)を使用しています。
