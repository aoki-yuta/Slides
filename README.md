# markdownをスライドで表示
markdownを書くだけでスライド表示\
[これ](https://github.com/yamap55/SlideWithGitHubPages)を使用

## URL

http://aoki-yuta.github.io/Slides/index.html?slide=**markdownPath**

ex)http://aoki-yuta.github.io/Slides/index.html?slide=slides/test.md

## 使いかた
### add slide
- Markdownでスライドを書く
  - 書き方は[検索](https://www.google.com/search?q=revelal.js+markdown)するか、[サンプル](https://raw.githubusercontent.com/yamap55/SlideWithGitHubPages/master/example/slide1.md)見てください。
- GitHubにpush
- 以下にアクセス
  - http://${userId}.github.io/${repositoryName}/index.html?slide=${markdownPath}

### print-pdf
- URL末尾に「&print-pdf」を付与して表示。
  - 例 : http://yamap55.github.io/SlideWithGitHubPages/index.html?slide=example/slide1.md&print-pdf
- ブラウザの印刷設定
- PDFに保存、横向き、背景のグラフィックにチェック
- 保存

