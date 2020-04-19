## Abstract

This project seeks to explore portfolio building techniques that will do well in bear markets. We look at quarterly and daily data that point to a stock being resistant to recessions and we sample portfolios to compare between resistant and non-resistant stocks. We find that some treatments give promising portfolios during both bull and bear markets. These naive results warrant more investigation into the relationship between these metrics and portfolio performance.



## Goals:
- Build a recession resistant portfolio of S&P 500 stocks that beats the overall market during bear markets while maximizing the Sharpe Ratio
- Compare naively constructed portfolios and Sharpe Ratio optimized portfolios against control portfolios
- Establish a proof of concept that will serve as a template for the continuation of building recession resistant portfolios 

<img src="https://github.com/capstonefiu2020/CAP2020_FINAL/blob/master/images/Sharpe_Ratio_Formula.png" width="470" height="200" />


<img src="https://github.com/capstonefiu2020/CAP2020_FINAL/blob/master/images/Sharpe_ratio.PNG" width="630" height="200" />
<img src="https://github.com/capstonefiu2020/CAP2020_FINAL/blob/master/images/Sharpe_ratio2.PNG" width="350" height="120" />





## Results:
### Experiment 1:
* The alternative portfolios produced significantly better results for both the ROE and PEG treatments. In particular, the ROE 
* treatment outperformed controls on both 2019 and recession data. 

### Experiment 2:
* The more the Alternative stocks beat the S&P 500 in 8/2008-12/2008, the better the Alternative portfolio performed in Q1 of 2020
* However there was no statistically significant separability between Alternaive and Control portfolios

## Conclusions:
* ROE and PEG portfolios performed very well
* Using the return threshold as a heuristic is a good start (Experiment 2) to estimate stocks eligible for alternative portfolios 
* Other metrics related to moving averages and D/E ratio need to added to alternative portfolio criteria
* The more stocks to select from, the large the sample space of alternative/control portfolio designs





You can use the [editor on GitHub](https://github.com/capstonefiu2020/CAP2020_FINAL/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown


Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

Here is more miareafsofije


```markdown
Syntax highlighted code block




# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/capstonefiu2020/CAP2020_FINAL/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
