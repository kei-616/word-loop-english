WORD LOOP ENGLISH — COMPLETE BUILD

【まずはこちら】
- Word_Loop_English_NYC_Complete.html: 画像を内蔵した単体HTML。前回と同じくHTMLファイル1つで構成。
- Word_Loop_English_PWA_Complete.zip: GitHub Pagesで公開してiPhoneのホーム画面に追加するための一式。

【収録内容】
- 語句データ 1,500件（基本見出し語 1,089 + 活用・派生形 411）。
- 発音表記 1,493件。CMU Pronouncing Dictionaryの発音をIPA風に変換した近似表記。端末の音声合成で読み上げ可能。
- 個別例文・訳 183件。語源・類義語の深掘り解説 10語分。未収録の項目は未収録と表示し、内容を推測で補っていません。
- TOEIC Part 7: 4文章セット・12問。Part 4: 50セット（オリジナル練習問題）。
- 4択単語クイズ、間違いリスト、ランダム復習、単語帳検索、発音読み上げ、読解採点・解説、Part 4スクリプト表示。
- 学習記録は利用中のブラウザに保存（localStorage）。端末間で自動同期はしません。

【iPhoneで使う場合】
単体HTMLをiPhoneの「ファイル」アプリのプレビューで開くと、iOS側のプレビュー制限でJavaScriptが動かないことがあります。iPhoneでアプリのように使うには、PWA ZIP内のファイルをGitHubリポジトリのルートへアップロードし、GitHub Pagesで公開してください。公開URLをSafariで開き、「共有」→「ホーム画面に追加」を選びます。

【GitHub Pagesの設定】
1. ZIPを展開し、中身（index.html、manifest.webmanifest、sw.js、画像・アイコン等）をリポジトリのルートへアップロード。
2. Repository > Settings > Pages > Deploy from a branch を選択。
3. Branch: main / Folder: /(root) を指定して保存。
4. 表示された https://ユーザー名.github.io/リポジトリ名/ をiPhoneのSafariで開く。
5. Safariの共有メニューから「ホーム画面に追加」。

【データ上の注意】
411件は辞書で綴りを照合した活用・派生形で、意味は原形をもとに表示しています。1,500件すべてが独立した見出し語という意味ではありません。カナ表記は全件ではなく、発音表記にも近似変換が含まれます。

CMU Pronouncing Dictionary attribution
Pronunciation references used: CMU Pronouncing Dictionary, Carnegie Mellon University.
The python-cmudict wrapper/package used during generation is distributed under GPL-3.0-or-later. The app includes transformed pronunciation strings only, not the dictionary database or wrapper code. See LICENSE-GPL-3.0.txt.
