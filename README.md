# Board Game Analysis・ボードゲームの分析

## Description

This project analyzes data provided to determine what type of board game would make the most money・このプロジェクトは提供されたデータを分析して、どの種類のボードゲームが最も収益を上げるかを決定します。

## data set・データセット
https://www.kaggle.com/datasets/jvanelteren/boardgamegeek-reviews

Data from board game geeks includes descriptions of board games, user reviews, and board game qualities (minimum players, age restrictions, etc.)

ボードゲームマニアからのデータには、ボードゲームの説明、ユーザーのレビュー、ボードゲームの品質 (最小プレイ人数、年齢制限など) が含まれます。

## Files
**"Stats for data science document.pdf"** Quarto Document analysis of the board game data set・データ分析のクワルトドキュメント

**"Stats for data science R code.qmd"** R code of the analysis・Rコード

## Summary of Analysis

1.) Prepare and describe the data and deciding performance measures・データを準備して説明し、パフォーマンス指標を決定する

2.) analysis・分析

3.) strategy recommendation・戦略の推奨

## Results・結果

### Significant Variables・重要な変数

- **Minimum Age・最低年齢**: Identified as the most significant predictor of board game success. Surprisingly, games with higher minimum age requirements tend to be more successful. This could be due to manufacturers' strategic age settings to avoid the costs of Children's Product Certificates.

ボードゲームの成功の最も重要な予測因子として特定されています。驚くべきことに、最低年齢要件が高いゲームほど成功する傾向があります。これは、子供向け製品証明書のコストを回避するためのメーカーの戦略的な年齢設定によるものである可能性があります。
  
- **Minimum Number of Players・最低人数**: Negatively correlated with success, indicating that games requiring fewer players are more successful.

成功と負の相関があり、プレイヤーの数が少ないゲームのほうが成功することを示しています。
  
- **Year of Publication・出版年**: Positively correlated with success, suggesting that newer games are more successful.

成功と正の相関があり、新しいゲームほど成功していることを示唆しています。

### Insights on Minimum Age・最低年齢に関する洞察
- The positive correlation between higher minimum age and success might be due to avoiding regulatory costs rather than reflecting actual game complexity or content.
- A density plot shows spikes at ages 8, 10, and 12, indicating a strategic setting of minimum ages to avoid additional certification costs.
- Other factors like reading level, thematic content, complexity, and piece size could also explain the correlation.

- 最低年齢の高さと成功との間に正の相関があるのは、実際のゲームの複雑さや内容を反映しているというよりも、規制コストを回避しているためである可能性があります。
- 密度プロットは、8 歳、10 歳、12 歳でのスパイクを示しており、追加の認定コストを回避するための最低年齢の戦略的な設定を示しています。
- 読書レベル、テーマの内容、複雑さ、作品のサイズなどの他の要因も相関関係を説明できる可能性があります。
  
### Potential Sampling Bias・サンプリングバイアス
- The site's user demographic may skew towards older age groups, influencing the success metrics.
  
サイトのユーザー層はより高い年齢層に偏り、成功指標に影響を与える可能性があります。

### Market Trends・市場動向

- The positive correlation with the year of publication reflects a growing interest and investment in board games over recent years.

- 出版年との正の相関は、近年のボードゲームへの関心と投資の高まりを反映しています。

### Limitations・制限事項
- Data on replayability, game mechanics, artwork quality, social relevance, production costs, retail prices, marketing budgets, and publisher reputation are missing.
- Including these variables would provide a more comprehensive analysis and actionable recommendations.

- リプレイ性、ゲームの仕組み、アートワークの品質、社会的関連性、制作コスト、小売価格、マーケティング予算、パブリッシャーの評判に関するデータが欠落しています。
- これらの変数を含めると、より包括的な分析と実用的な推奨事項が提供されます。

## Conclusion・結論
The current analysis lays a solid foundation for understanding board game success. Incorporating additional data and addressing the limitations would lead to a more nuanced and informed strategy for maximizing board game success.

現在の分析は、ボードゲームの成功を理解するための強固な基盤を築きます。追加のデータを組み込み、制限に対処することで、ボード ゲームの成功を最大化するための、より微妙な情報に基づいた戦略が生まれます。
