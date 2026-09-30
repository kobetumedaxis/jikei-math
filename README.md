# jikei-math
東京慈恵会医科大学の数学問題冊子風 LuaLaTeX テンプレート
# 慈恵医大 数学問題冊子風 LaTeX Template

東京慈恵会医科大学の数学問題冊子風のレイアウトを再現した
LuaLaTeX用テンプレートです。

## 使用環境

- LuaLaTeX
- jlreq
- LuaTeX-ja
- LaTeX Workshop（VS Code）

## 使い方

LaTeXを使ったことがない方でも、以下の手順で使用できます。

### 1. VS Codeをインストールする

「VS Code」と検索し、Microsoftの公式サイトから
**Visual Studio Code** をダウンロードしてインストールしてください。
（検索すると基本的に一番上に出てきます）

Windows・Macどちらでも使用できます。

### 2. TeX環境をインストールする

使用しているOSに合わせてTeX環境をインストールしてください。

#### Macの場合

「MacTeX」と検索し、公式サイトから
**MacTeX** をダウンロードしてインストールしてください。

#### Windowsの場合

「TeX Live Windows」と検索し、公式サイトから
**TeX Live** をダウンロードしてインストールしてください。

※TeX環境はファイルサイズが大きいため、
インストールに時間がかかる場合があります。

### 3. LaTeX Workshopをインストールする

VS Codeを開き、左側にある四角が並んだ
**Extensions（拡張機能）** のアイコンを押します。

検索欄に

    LaTeX Workshop

と入力し、表示されたものをインストールしてください。

### 4. このテンプレートをダウンロードする

このGitHubページ上部にある緑色の **「Code」** ボタンを押し、

**Download ZIP**

を選択してください。

ダウンロードしたZIPファイルを展開し、
中にある `jikei-math-code.tex` をVS Codeで開いてください。

### 5. 問題を編集する

VS Codeで `jikei-math-code.tex` を開き、
問題文や数式を自分が使用したい問題に書き換えてください。

問題を追加したい場合は、問題部分の

    \newpage

からその問題の末尾までをコピーし、

    \end{document}

の直前に貼り付けてください。

問題番号などは適宜変更してください。

ファイル先頭の

    % !TeX program = lualatex

は削除しないでください。

### 6. PDFを作る

編集が終わったら、VS Code左側にある **TeX** のアイコンを押してください。

**COMMANDS** を開き、

1. **Build LaTeX project**
2. **View LaTeX PDF**

の順番に押します。

PDFが表示されれば完成です。

必要に応じてPDFを保存して使用してください。

## 注意

本テンプレートは非公式のものであり、
東京慈恵会医科大学とは一切関係ありません。

レイアウト作成用のテンプレートとして公開しています。
