# uiflow-notes
uiflowを使った既存サービスの写経メモ置き場

## 目的
既存Webサービスの画面遷移を写経することで、どのようにUI設計がされているかを学ぶため。

## 使うツール
画面遷移の表現に、**uiflow**というフレームワークを使います。
- [A shorthand for designing UI flows ](https://signalvnoise.com/posts/1926-a-shorthand-for-designing-ui-flows)
- [もう保守されない画面遷移図は嫌なので、UI Flow図を簡単にマークダウンぽく書くエディタ作った](https://qiita.com/hirokidaichi/items/ff54a968bdd7bcc50d42)

利点として、
- 「ユーザーが見るもの」「ユーザーがすること」を繋げていくだけだから、シンプル
- 余計な情報がないので、「動機」と「行動」の連鎖が明確でないような画面を発見しやすい
- 一覧性が高い
- Markdown形式で書いてGitHub管理できる

uiflowの記述には**vscode-uiflow**を使い、Markdown形式で管理できるようにしています。
- [uiflowのvscodeプラグインを作ってみました](https://qiita.com/kexi/items/f5bd25fd4a7da81e62d4)

## 約束事
### ディレクトリ構成
- {serviceName}
    - {date}_{scinario}.txt : uiflow作成用
    - {date}_{scinario}.md : ページ表示用
    - {date}_{scinario}.png : uiflow図
- こうしておけば1日で網羅できなかったり、途中で飽きたりしても画面ごとなので再開が容易。

### 書くこと
- 画面遷移図(uiflow)
- 気付きを箇条書きで3つ
