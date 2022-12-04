# Sephiroth
Zoom SDK and AI

## 参考
### 日本語音声起こしライブラリ
https://qiita.com/ysugiyama12/items/bf246e80ae4d1dc16441

### 議事録から文字起こししてるらしい
https://rserver-osusume.com/ai-with-python/voice-recognit

### リアルタイム音声認識
https://qiita.com/hamham/items/9b553d0759a2319ea211

https://www.netone.co.jp/knowledge-center/netone-blog/20220314-1/

### Cloud Speech-to-Text Document
https://cloud.google.com/speech-to-text/docs/async-recognize?hl=ja

#### メモ
営業と顧客の会話を非同期に文字として、
サーバに上げていく。テキストファイルを作成する？
顧客か営業のどちらが話をしたかの判断基準が必要。

会話→API呼び出し→テキストファイル作成→DBに挿入？？
→挿入された文字列を元にAIが基準を返却する

