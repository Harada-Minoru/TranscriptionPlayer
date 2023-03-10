# テープ起こしプレイヤー
テープ起こしのための音声再生ソフトです。  
ベータ版なので、機種によって動作が不安定になったり、読み込めないなどの不具合があるかもしれません。  
ご了承の上お使いください。

## 使用概観

<img width="960" alt="image" src="https://user-images.githubusercontent.com/102857572/222118588-1508f55c-b529-40ea-a756-f97133c7a711.png">

**主な機能**
- 文字を邪魔しない半透明のUI
- 再生速度を0.25倍速～2倍速まで変更可能
- 1, 3, 5, 10, 15, 30, 60秒で巻き戻し、早送り可能
- 巻き戻し、早送りはショートカットキー対応
- 再生位置を hh:mm:ss の形式でクリップボードにコピー可能

## セットアップ方法
1. Zipファイルを[GitHub](https://github.com/Harada-Minoru/TranscriptionPlayer/blob/main/%E3%83%86%E3%83%BC%E3%83%97%E8%B5%B7%E3%81%93%E3%81%97%E3%83%97%E3%83%AC%E3%82%A4%E3%83%A4%E3%83%BC.zip)からダウンロード

<img width="914" alt="image" src="https://user-images.githubusercontent.com/102857572/222121373-6b133b08-97ad-4b05-92c9-10ebfeae3796.png">

2. ダウンロードしたZipファイルを展開
3. 展開したフォルダ内の "TranscriptionPlayer.exe" を起動

- 起動の際に、Windowsによって以下のような不明の発行先に関する警告がでることがあります。<br>
起動するには、「詳細情報」→「実行」をクリックしてください。
- 非公式のソフトということで、稀にセキュリティソフトに引っかかってしまうことがあります。

<img width="401" alt="image" src="https://user-images.githubusercontent.com/102857572/222116445-630ce940-f6ab-48bd-b3e6-b032404a6190.png">

## 各部の機能と使い方
<img width="764" alt="image" src="https://user-images.githubusercontent.com/102857572/222126569-d9e21d55-e06f-4030-8d2e-92bbe76db3ec.png">

### 1. 音声ファイルを開く  
左上の「開く」ボタンをクリックすると、ダイアログが表示されて音声ファイルを選択することができます。
対応フォーマットは: mp3, wav, .wma, aac などの一般的な音声ファイル形式です。
正常にファイルが開かれると再生できるようになります。

### 2. 再生・停止  
真ん中の ⏸ ▶ ボタンを押すことで再生・停止できます
ショートカットキーは Ctrl+Space です。

### 3. 再生位置変更  
真ん中のスライダーを動かすことで変更できます。

### 4. 巻き戻し・早送り  
基本的な巻き戻し・早送りのショートカット機能として、
- Alt + ←キー: 3秒巻き戻し
- Alt + →キー: 3秒早送り  
が可能です。

また、3秒以外の巻き戻しや早送りにも対応しています。
再生・停止ボタンの左右に 1, 5, 10, 15, 30, 60秒ごとの巻き戻し・早送りボタンがあります。
それらをクリックすることで、現在の再生位置から指定した秒数シフトすることができます。  
ショートカットキーは以下の通りです。(数字キーはテンキーではない方です。)

| 秒数 | 1秒 | 5秒 | 10秒 | 15秒 | 30秒 | 60秒 |
| ------ |-------|--------|-------|-------|-------|-------|
| 巻き戻し |Ctrl+1       |Ctrl+2         |Ctrl+3       |Ctrl+4       |Ctrl+5       |Ctrl+6       |
| 早送り |Shift+Ctrl+1       |Shift+Ctrl+2         |Shift+Ctrl+3       |Shift+Ctrl+4       |Shift+Ctrl+5       |Shift+Ctrl+6       |

### 5. 再生位置コピー機能  
このボタンをクリックすると、現在の再生位置(hh:mm:ss形式)がクリップボードにコピーされます。
テープ起こしの文章に再生位置を打ち込みたい際に便利です。  
ショートカットキーは、Shift+Ctrl+C です。

### 6. 再生位置読込機能  
再生位置を hh:mm:ss 形式で示したものをクリップボードにコピーした状態でこのボタンをクリックすると、
その再生位置に移動することができます。5.で打ち込んだ再生位置からもう一度再生したい場合に便利です。
ショートカットキーは、Shift+Ctrl+V です。

### 7. 最前面  
これにチェックをつけると、ウィンドウを最前面に保持することができます。

### 8. 再生速度  
このスライダーを動かすことで、音声の再生速度を 0.25～2倍まで変化させることができます。
急にスライダーを動かしすぎると稀に音声が止まります。優しく扱ってあげましょう。
