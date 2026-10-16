tool_bas2load
PB-100 の BASIC テキストを、実機の LOAD で読み込める形式に変換するツールです。

■ 動作環境
  Windows。tool_bas2load.exe だけで動きます。

■ 使い方
  tool_bas2load 名前.bas              名前.load.txt を作成
  tool_bas2load 名前.bas 出力.txt     出力先を指定
  tool_bas2load -d 受けたログ.txt     実機で SAVE したものを BASIC テキストに戻して表示
  tool_bas2load [help]                使い方を表示 (help は省略可)

■ LOAD 手順
  1) 実機 (PB-100) で LOAD を実行
  2) 作成したファイルをターミナルソフトからファイル送信

■ BASIC テキストの書き方
  - 行番号は 1〜9999、小さい順に並べる
  - PB-100 の特殊文字は \ を付けて書く (例: \NE ≠  \LE ≦  \GE ≧  \PI π  \\ 円記号)
  - PB-100 にない文字や命令があると、エラーを表示して変換しません

■ ご注意
  - 動作確認は手持ちの PB-100 (無印) でのみ行っています。
  - 本ツールは無保証です。ご利用は自己責任でお願いします。
  - 正式なサポートを行うかは未定です。
