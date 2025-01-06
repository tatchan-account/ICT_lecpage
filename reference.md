# 参考文献・記号
## 記号
本ページで暗黙のうちに用いている数学の記号は次のことを意味しています(各数の集合の定義は細かくは立ち入らないことにしています)。
- $\mathbb{N}$／自然数の集合。具体的には$\mathbb{N} = \{ 0, 1, 2, \cdots \}$です。
- $\mathbb{Z}$／整数の集合。ここでは、$\mathbb{N}$の元の和に関する逆元として定めます。
- $\mathbb{Q}$／有理数の集合。ここでは、$\mathbb{Q}=\left\{\frac{n}{m} : m, n \in \mathbb{Z} \right\}$とします。
- $\mathbb{R}$／実数の集合。ここでは、有理数の切断を用いて$\mathbb{R}=\left\{\alpha = (A,A') : (A,A'){は有理数の切断}\right\}$と定めることにします。
	- 有理数の完備化によって構成しても構いません。$A:=\{{x_n}:{x_n}{は有理数のコーシー列}\}$に対して、同値関係$\displaystyle\{x_n\} \sim \{y_n\}:\iff \lim_{n\to \infty} |x_n - y_n|=0$を用いて、$\mathbb{R}:=A/\sim$と定めることもできます。

## 参考文献
### 書籍
```{bibliography}
:all:
```

### ドキュメント等
- [Jupyter Book](https://jupyterbook.org/en/stable/intro.html)
	- ページと実行環境の開発環境
- [機械学習帳](https://chokkan.github.io/mlnote/index.html)
	- 東京工業大学(現東京科学大学)情報工学系の岡崎先生の講義資料
	- こちらもオープンソースでコードが使用可能
	- 今回のコードも大変参考にさせていただきました。感謝申し上げます。
- [Python](https://www.python.org/)
	- 書きやすい言語
	- 公式ドキュメントだけでなくChatGPTを効果的に使うと、スムーズなコーディングが可能
- [NumPy](https://numpy.org/)
	- 数学的なことをする際には必須アイテム
- [Matplotlib](https://matplotlib.org/stable/)
	- 数値など、あらゆる数をプロットできるアイテム
	- とてもわかりやすい公式ドキュメントがあるので、それを参考にコーディングするのが一番