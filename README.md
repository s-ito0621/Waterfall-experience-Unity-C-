# Waterfall-experience-Unity-C-

# ファイルとフォルダの説明
## Arduino関連/
* *UduinoCytronEZMP3*
    * 頭と両肩に振動を与えるArduinoのマイコンの制御に使うライブラリのプログラム
* *UduinoTakiVrHead*
    * 頭に振動を与えるArduinoのマイコンに書き込むプログラム
* *UduinoTakiVrLR*
    * 両肩に振動を与えるArduinoのマイコンに書き込むプログラム。
## TakiVR
* *TakiVR.unitypackage*
    *Unityのプロジェクト(重すぎてUploadしていないので、必要であればぜひ。。。)

# 使用方法
※Uduinoを使用する場合「Uduinoライブラリ」を絶対に購入しておいてください。

## インポート方法
「TakiVR.unitypackage」はUnityのプロジェクトパッケージです。このリンクに従ってimportしてください。
実験のシーンは「/Scenes/TakiVR」です。
シュミレーターモードなのでVRでは動きません。シュミレーターの操作方法はこのリンクに従ってください。
VRで動かしたい場合
TakiVRシーンのHierarchy上にある「XR Device Simulator」オブジェクトをこのリンクのように無効化
このリンクのように「Initialize XR on Startup」のチェックボックスを”付けてください”
「Arduino関連.zip」arduino・Uduino用のプログラムも添付しておきます。
「UduinoCytronEZMP3」フォルダはこのマイコン用のライブラリです
「UduinoTakiVrHead」フォルダは頭用のマイコンに書き込んだものです。
「UduinoTakiVrLR」フォルダは両肩用のマイコンに書き込んだものです。
