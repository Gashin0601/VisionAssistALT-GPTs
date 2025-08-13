# VisionAssist ALT GPTs

VisionAssist ALTは、視覚障害者向けにALT（画像説明）を自動生成するChatGPT-GPTsのオープンソースプロジェクトです。  

詳しい使い方や利用規約は、公式サイトをご覧ください：  
https://vision-assist-alt-node-js.vercel.app/

現行最新版: Ver.2.0-beta

## ファイル構成

- **`visionassist-alt.md`**  
  GPTsのプロンプトを記載しています。自由に二次利用可能です。  
  開発者向けドキュメントはこちら：  
  https://vision-assist-alt-node-js.vercel.app/developers

## バージョン

- **Ver.2.0-beta**  
  変更:
  - ツイート本文をチャットに入力された際には、ニュアンス（意図・語調・強調点）を読み取りALTに反映
  - 複数画像に対応し、各画像ごとに独立したALTコードブロックを出力
  - 最初に端的な一文（必要な情報を短く）→ 続けて詳細説明の順で記述
  - 鳥・花の種名は可能な限り特定（不確実な場合は一般名＋根拠）
  - 具体的名称（場所・施設名など）は直接表現
  - 数式はLaTeXを使わず文章で記述
  - 日付・時刻は日本語表記に正規化（例: 7/21 10:30 → 7月21日 10時30分）
  

- **Ver.1.0**  
  https://github.com/Gashin0601/VisionAssistALT-GPTs/blob/d1fd87f6d830375385a48d649c013383abfa0e65/visionassist-alt.md

## ライセンス

© GCStudio 2024