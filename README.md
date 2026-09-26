# 苹果翻转棋

在线对弈：https://penzai-py.github.io/apple-othello/

一个从零自对弈训练出的翻转棋 AI。`index.html` 是自包含的单文件页面：
翻转棋规则和一个 30 万参数的卷积网络都用 JavaScript 在浏览器里运行，不需要服务器。
AI 每步只看网络对每个落点的终局子差估值，选最大的，不做搜索。
