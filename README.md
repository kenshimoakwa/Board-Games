# Board Game Analysis

## Description

This project analyzes data provided to determine what type of board game would make the most money.

## data set
https://www.kaggle.com/datasets/jvanelteren/boardgamegeek-reviews

Data from board game geeks includes descriptions of board games, reviews from users, and board game qualities (minimum players, age restrictions, etc.)

## Files
**"Stats for data science document.pdf"** Quarto Document analysis of the board game data set

**"Stats for data science R code.qmd"** R code of the analysis
## Summary of Analysis

1.) Prepare and describe the data and deciding performance measures

2.) analysis

3.) strategy recommendation

## Results

### Significant Variables
- **Minimum Age**: Identified as the most significant predictor of board game success. Surprisingly, games with higher minimum age requirements tend to be more successful. This could be due to manufacturers' strategic age settings to avoid the costs of Children's Product Certificates.
- **Minimum Number of Players**: Negatively correlated with success, indicating that games requiring fewer players are more successful.
- **Year of Publication**: Positively correlated with success, suggesting that newer games are more successful.

### Insights on Minimum Age
- The positive correlation between higher minimum age and success might be due to avoiding regulatory costs rather than reflecting actual game complexity or content.
- A density plot shows spikes at ages 8, 10, and 12, indicating a strategic setting of minimum ages to avoid additional certification costs.
- Other factors like reading level, thematic content, complexity, and piece size could also explain the correlation.

### Potential Sampling Bias
- The site's user demographic may skew towards older age groups, influencing the success metrics.

### Market Trends
- The positive correlation with the year of publication reflects a growing interest and investment in board games over recent years.

### Limitations
- Data on replayability, game mechanics, artwork quality, social relevance, production costs, retail prices, marketing budgets, and publisher reputation are missing.
- Including these variables would provide a more comprehensive analysis and actionable recommendations.

## Conclusion
The current analysis lays a solid foundation for understanding board game success. Incorporating additional data and addressing the limitations would lead to a more nuanced and informed strategy for maximizing board game success.
