# Waterfall-experience-Unity-C-

# ファイルとフォルダの説明
## Arduino関連/
* *UduinoCytronEZMP3*
    * 頭と両肩に振動を与えるBass shakerに音楽を再生するためのライブラリのプログラム [こちら](https://elefine.info/shield-ezmp3/)を参考
* *UduinoTakiVrHead*
    * 頭に振動を与えるArduinoのマイコンに書き込むプログラム
* *UduinoTakiVrLR*
    * 両肩に振動を与えるArduinoのマイコンに書き込むプログラム。
## TakiVR
* *TakiVR.unitypackage*
    * Unityのプロジェクト(重すぎてUploadしていないので、必要であればぜひ。。。)

# 使用方法
※Uduinoを使用する場合「Uduinoライブラリ」を絶対に購入しておいてください。

## インポート方法

1. 「TakiVR.unitypackage」はUnityのプロジェクトパッケージです。[このリンク](https://kan-kikuchi.hatenablog.com/entry/Unitypackage)に従ってimportしてください。
2.  実験のシーンは「/Scenes/TakiVR」です。
3.  シュミレーターモードなのでVRでは動きません。シュミレーターの操作方法は[このリンク](https://tech.framesynthesis.co.jp/unity/xr/#:~:text=%E3%81%A6%E3%81%8F%E3%81%A0%E3%81%95%E3%81%84%E3%80%82-,%E3%83%98%E3%83%83%E3%83%89%E3%82%BB%E3%83%83%E3%83%88%E3%81%AA%E3%81%97%E3%81%A7XR%20Origin%E3%82%92%E6%93%8D%E4%BD%9C%E3%81%99%E3%82%8B%E3%81%AB%E3%81%AF,-XR%20Device%20Simulator)に従ってください。
## VRで動かしたい場合
1.  TakiVRシーンのHierarchy上にある「XR Device Simulator」オブジェクトを[このリンク](https://tech.pjin.jp/blog/2021/03/31/unity_gameobject_component_on-off/)のように無効化
2.  [このリンク](https://yotiky.hatenablog.com/entry/2021/12/06/unity_xrpluginmanagement-runineditor)のように「Initialize XR on Startup」のチェックボックスを”付けてください”

