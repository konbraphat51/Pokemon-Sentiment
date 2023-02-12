# 5ch極性分析システム
## 概要
* 5chからキーワードが合致するテキストをスクレイピング(01-03)
* 手動ラベリング補助ソフト（05）  
こちら（ https://konbraphat51.github.io/Text-Labeling/ ）で確認できます  
* アマゾンレビューから極性の学習データを取得（06）
* 5ch全体からランダムに母集団となるテキストデータをスクレイピング(07, 08)
* 極性分析モデルを生成（09）
* 重要語の表示、重要語ごとの極性スコアを算出（10）
![image](https://user-images.githubusercontent.com/101827492/218311706-50469fdb-bdd9-44cd-abd5-86dd3f5aac6c.png)
* 重要語に共起する単語を表示（11）
* キーワードの極性の変遷を表示（12）
  
## 使い方
各ノートの「必要なもの」の指示にしたがった後に実行してください。  
極性ラベリングをする際は「pos」「neg」「neu」の三択、あるいは「pos」「neg」「neu」「resb」（レスバ）の４択で行ってください。
  
## 分析例
ミミッキュ：https://github.com/konbraphat51/Sentiment-Analysis-mimikkyu  
ピカチュウ：https://github.com/konbraphat51/Sentiment-Analysis-Pikachu  
（失敗例）東大生：https://github.com/konbraphat51/Sentiment-Analysis-UT-sei  
