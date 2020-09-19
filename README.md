# respect_my_cryptin'
## About
The goal of this project was to apply natural language processing to understand the sentiment in the latest headlines about Bitcoin and Ethereum. In the end, using things like nltk, spaCy, and some beautiful functions, I did just that. 

### Hypothesis
I expected to see more articles/discussion about Bitcoin but an overall higher positive sentiment for Ethereum. 

Ethereum would have the more positive sentiment because it is more than just a cryptocurrency and people are really invested in blockchain technology and smart contracts.


### Findings
I initially used the news api and nltk's sentiment analyzer to find the overall sentiment of my articles. I originally pulled 20 articles for Bitcoin and 16 articles for Ethereum. To then make the analysis equal I took the top 16 articles from the Bitcoin data.

Here I have the sentiment scores for the Bitcoin articles.
![Bitcoin Sentiment Scores](~/images/bitcoin_data.png)

As already stated, I took the top 16 articles from Bitcoin to have an equal pool for the Ethereum sentiment comparisons. Here is the sentiment for those articles.
![Bitcoin Top 16](~/images/bitcoin_top16.png)

Here I have the sentiment scores for the Ethereum articles.
![Ethereum Sentiment Scores](~/images/ethereum_data.png)

After looking at the sentiment scores I then did a deeper analysis of the actual words in the articles. I have included some word cloud visuals for a quick synopsis of my findings.

Here I have the word cloud for Bitcoin.
![Bitcoin Word Cloud](~/images/bitcoin_wordcloud.png)

Here I also have the word cloud for Ethereum.
![Ethereum Word Cloud](~/images/ethereum_word_cloud.png)

I broke my final analysis into three questions that I feel give the strongest representation of the data. I will now state and answer each question below.


**1. Which coin had the highest mean positive score?**

Ethereum analysis ended up involving 16 articles and concluding with a mean positive score of 0.063062 while Bitcoin analysis ended up involving 20 articles having a mean positive score of 0.075000. Therefore, we can clearly see that Bitcoin has a higher mean positive score. One could argue that this is because there are 4 more articles to analyze. I took this argument into account and then did a second analysis of Bitcoin but only with 16 articles. Bitcoin still beats Ethereum with a mean positive Score of 0.071250.

**2. Which coin had the highest compound score?**

Since I have two versions of Bitcoin I will give each. When I used all 20 articles my Bitcoin data had a max compound score of 0.750600. Looking at the 16 articles Bitcoin still maxed at 0.750600. Ethereum had a max compound score of 0.757900. This means that Etherum ended up beating both groups of Bitcoin data. In an overall scheme of things, this would technically mean that there's are more positive sentiment overall about Ethereum than Bitcoin. 

**3. Which coin had the highest positive score?**

Again looking at my multiple versions of Bitcoin, my group of 20 articles had a max positive score of 0.198000 and my group of 16 articles had a max positive score of 0.198000 as well. Ethereum ended with a max positive score of  0.20900. From looking at all three of these questions. Ethereum is looking like a better investment.

#### Conclusion
My hypothesis was pretty much correct. Ethereum won all over, but Bitcoin still had a positive sentiment. Bitcoin actually has the highest mean positive score, but that could mean that Ethereum had more neutral articles. This could be because Ethereum has a vast amount of topics that could be discussed and these could solely be discussions explaining Ethereum. Ethereum had a higher compound score as well as the highest positive score. One has to still remember that the numbers were all pretty close. I still believe that Ethereum would be the better investment. 



