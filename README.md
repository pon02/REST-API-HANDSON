# REST-API-HANDSON
## GETリクエスト
⭐︎ curlコマンドでユーザー情報を表示  

<img width="400" alt="スクリーンショット 2024-01-11 12 14 27" src="https://github.com/pon02/REST-API-HANDSON/assets/140311845/eddd615c-eebe-420a-9c73-49ad17638c3b">


実行結果200


⭐︎ POSTMAN GETリクエストでユーザー情報を表示

<img width="400" alt="スクリーンショット 2024-01-11 12 06 56" src="https://github.com/pon02/REST-API-HANDSON/assets/140311845/dd3bf584-f7df-422f-a736-ec64e48fc75f">
  

実行結果200  

## POSTリクエスト
⭐︎ curlコマンドでリポジトリの作成  

<img width="400" alt="スクリーンショット 2024-01-11 12 51 04" src="https://github.com/pon02/REST-API-HANDSON/assets/140311845/2e47698e-09a9-403a-96d7-94a24eb12d27">


実行結果201

<img width="400" alt="スクリーンショット 2024-01-11 14 23 01" src="https://github.com/pon02/REST-API-HANDSON/assets/140311845/f46fdbaa-f247-4ed1-85f7-a505585ca4d6">  

新規のリポジトリ「blog」が作成された。  

⭐︎ POSTMAN POSTリクエストでblog02を作成

<img width="400" alt="スクリーンショット 2024-01-11 13 46 52" src="https://github.com/pon02/REST-API-HANDSON/assets/140311845/73af6696-6a81-47c8-8ac3-149c32d77c18">
  

実行結果201　　

<img width="400" alt="スクリーンショット 2024-01-11 13 49 24" src="https://github.com/pon02/REST-API-HANDSON/assets/140311845/10d1b2b9-2c7e-4d59-80c7-ce4795a51be9">  

新規のリポジトリ「blog02」が作成された。  

## PATCHリクエスト

⭐︎ curlコマンドでリポジトリの情報変更  
<img width="400" alt="スクリーンショット 2024-01-11 13 55 47" src="https://github.com/pon02/REST-API-HANDSON/assets/140311845/4dcf1901-6338-4bea-b9bc-b72da5b92435">  

実行結果200  

<img width="400" alt="スクリーンショット 2024-01-11 13 57 08" src="https://github.com/pon02/REST-API-HANDSON/assets/140311845/3d627384-4b11-47ee-80ac-ce082d3ab83d">  

情報が更新された。  

⭐︎ POSTMAN PATCHリクエストでリポジトリの情報変更

<img width="400" alt="スクリーンショット 2024-01-11 14 35 04" src="https://github.com/pon02/REST-API-HANDSON/assets/140311845/857457ce-b468-44b2-9e24-b1701896b1de">  

実行結果200  

<img width="400" alt="スクリーンショット 2024-01-11 14 36 06" src="https://github.com/pon02/REST-API-HANDSON/assets/140311845/4686dfe5-048d-4bbf-b83c-7b83a56a4949">  

情報が更新された。  

## DELETEリクエスト

⭐︎ curlコマンドでリポジトリ削除

<img width="400" alt="スクリーンショット 2024-01-11 16 15 20" src="https://github.com/pon02/REST-API-HANDSON/assets/140311845/ac3c3a03-d161-40bf-9183-0184563f0daf">  

実行結果204  
リポジトリが削除された。  


⭐︎ POSTMAN DELETEリクエストでリポジトリ削除

<img width="400" alt="スクリーンショット 2024-01-11 16 20 49" src="https://github.com/pon02/REST-API-HANDSON/assets/140311845/4b2f30d8-d91f-4036-a373-2311917ceba6">  

実行結果204  
リポジトリが削除された。  

<img width="400" alt="スクリーンショット 2024-01-11 16 27 30" src="https://github.com/pon02/REST-API-HANDSON/assets/140311845/69d35584-39bf-483b-830d-f573dcc223c8">  


# ハンズオンを行ってみて
一通りの内容は実行することができた。
ターミナルからコマンドでPC内にディレクトリを作成などができるように、curlコマンドでネット上のWebサイトの操作ができるということが作業を通して理解できた。  
また同様のことをPOSTMANから、より視覚的にわかりやすい作業で行うことができることと、おおまかな操作方法も理解できた。 
REST APIが理解できたのかというとまだ輪郭に靄がかかっている状態だが、今回はこういう作業をすることができるのがREST APIということがわかったというところを結果とする。
ただ、curlコマンドのオプションについてはまだ理解が進んでおらず、POSTMANのリクエストの際のボディの記載は自分1人では何を書いたら良いかわかっていない状態で、ヘッダにどんな種類があるのかなどまだまだ調べることもたくさんあり、今後も地道に行っていく必要を感じた。  
