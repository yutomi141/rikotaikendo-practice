# rikotaikendo-practice

理工体剣道部の公式サイトを、自分の手で縮小版として作り直しながら Web 開発を学ぶ練習リポジトリ。

## 教材

| 巻 | 内容 | PDF |
|---|---|---|
| 第1巻 | 準備と、はじめての Web ページ（環境構築・Git・Claude Code・HTML/CSS/JavaScript） | [vol1.pdf](docs/textbook/vol1.pdf) |
| 第2巻〜 | 準備中 | — |

全体の構成は [docs/textbook/全巻構成.md](docs/textbook/全巻構成.md)。

## 進め方

1. 教材の PDF を上から順に進める
2. 進み具合は先輩と共有しているスプレッドシートで管理する
3. 第2巻からは、このリポジトリでブランチを切って PR を出す（`main` に直接 push しない）

## 教材のビルド（先輩用）

```bash
cd docs/textbook/vol1 && latexmk vol1.tex && cp build/vol1.pdf ../vol1.pdf
```

LuaLaTeX と `jlreq`・`piton`・`tcolorbox` が必要。フォントはヒラギノを使う（macOS）。
