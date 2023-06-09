# M5Unified_StackChan_ChatGPT_CoreS3_FaceDetect_LCD
M5Stack CoreS3のカメラ画像をLCDユニットに表示するｽﾀｯｸﾁｬﾝです。

ronron-ghさんの[M5Unified_StackChan_ChatGPT_Google_CoreS3_FaceDetectExample](https://github.com/ronron-gh/M5Unified_StackChan_ChatGPT_Google_CoreS3_FaceDetectExample/ "Title")に以下の改造を加えました。<br>

1. CoreS3のカメラ画像をLCDユニットに表示するように改造しました。<br>
2. 顔を検出するとｽﾀｯｸﾁｬﾝが話しかけてくるように改造しました。<br>


[LCDユニット](https://www.switch-science.com/products/7358/ "Title")をM5Stack CoreS3の PORT.A に接続しておく必要があります。<br>
Groveケーブルは10㎝ぐらいの短いものを使用してください。<br>
【注意】時々リセットが掛かります。<br>

---

# M5Unified_StackChan_ChatGPT_Google_CoreS3_FaceDetectExample

[robo8080さんの完全体AIｽﾀｯｸﾁｬﾝ](https://github.com/robo8080/M5Unified_StackChan_ChatGPT_Google)に、顔検出を組み込んだプログラムを参考例として公開します。  
※VoiceBoxバージョン（完全体AIｽﾀｯｸﾁｬﾝ2）ではありません。  
※顔検出単体のプログラム例はこちらです→　https://github.com/ronron-gh/M5CoreS3_FaceDetect

顔検出するとｽﾀｯｸﾁｬﾝが聞き取りを開始します。

LCDの中央付近をタッチしてサーボ停止モードにしている間は、LCDにカメラ画像を表示します。（このモードにした瞬間、たまにリセットが発生するバグがあります。）
