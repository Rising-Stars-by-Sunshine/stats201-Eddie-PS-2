# Prediction of Monthly Carbon Emissions
## Project information
- **Author**: Eddie Lin, Computation and Design major Computer Science track, 2025, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**:  Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: Thanks to Prof. Luyao for insightful comments in improving the research question and the inspiring lectures, special thanks to my classmates for the interesting discussions in class.
- **Project Summary**: 

**Explanation**: The amount of research in the field of Non-Fungible Tokens(NFT) is large enough for humans to be not able to understand what are the most focused aspects in research literatures in the NFT field. With the help of explanation machine learning algorithms, it is easy to find out the most discussed topics in NFT research. The goal of this research is to answer the question: What phrases are the most mentioned among NFT research papers? Seventeen pieces of literature related to NFTs were collected and had their titles and abstracts inspected. The inspection was carried out by Explanation machine learning algorithms, natural language processing was used to process the data, wordclouds and bigrams were created as results. The results shows highly frequent phrases used in the papers' titles and abstracts. This project gives insights to people both inside and outside the NFT field of what current research on NFTs are focused on, and potentially inspires researchers on which topics in the NFT field is more worth researching on.

**Prediction**: Carbon emissions is the primary factor that affects climate change, thus governments often use carbon/greenhouse gas emissions as a metric in making decisions around carbon-emitting human activities such as manufacturing and fuel-burning. It would be helpful to decisive government departments to know the possible carbon emissions in the future months so that they could make better responses to meet the carbon emission standards. This research wants to answer the question: How well can prediction algorithms in machine learning predict future month's carbon emission using the past month's carbon emission? The data uses monthly average global carbon emissions that was collected monthly from March 1958 to February 2023. Methods used in this study include Linear regression and random forest regressor as models in regressing, and the R-squared scorewas used as the metric to interpret the accuracy of each model. The results show that the linear regression model was accurate in predicting the future month's carbon emissions while the random forest regressor did poorly in predicting. I anticipate this study would inspire more studies to apply other prediction models to this field.


## Table of Contents
| File | Content |
| :---         |:---|
| [Data](https://github.com/Rising-Stars-by-Sunshine/stats201-Eddie-PS-2/tree/main/data) | [Data](https://github.com/Rising-Stars-by-Sunshine/stats201-Eddie-PS-2/edit/main/README.md#data)|
| [Code](https://github.com/Rising-Stars-by-Sunshine/stats201-Eddie-PS-2/tree/main/code) | [Code](https://github.com/Rising-Stars-by-Sunshine/stats201-Eddie-PS-2/edit/main/README.md#code)|
| [Spotlight](https://github.com/Rising-Stars-by-Sunshine/stats201-Eddie-PS-2/tree/main/spotlight) |[Spotlight](https://github.com/Rising-Stars-by-Sunshine/stats201-Eddie-PS-2/edit/main/README.md#spotlight)|


## Data
### Meta Data Information
| Data Files| Data Content | Data Type|
| :---         |     :---     | :---: |
|co2_mm_mlo.csv| data of monthly global carbon emissions | Queried |
|Cited.csv | literatures collected for the explanation task of the problem set | Queried |
|Regression_Test.csv| Test data for regression task| Processed |
|Regression_Train.csv| Train data for regression task| Processed |

### Data Dictionary 
| File of Data| variable name | description | frequency     |  unit. |    type|
|:---| :---         |     :---     |   :---: |  :---:   | :---: |  
|   co2_mm_mlo.csv    |      average     |    monthly average of global carbon dioxide emissions  |   monthly    |   parts per million    |    float64   |
|Cited.csv | title| title of each collected literature | \ | \ | String |
|Cited.csv | abstract| abstract of each collected literature | \ | \ | String |
|Regression_Test.csv| average|  monthly average of global carbon dioxide emissions | monthly | parts per million | float64|
|Regression_Test.csv| average_past|  average of global carbon dioxide emissions of the past month | monthly | parts per million | float64|
|Regression_Train.csv| average|  monthly average of global carbon dioxide emissions | monthly | parts per million | float64|
|Regression_Train.csv| average_past|  average of global carbon dioxide emissions of the past month | monthly | parts per million | float64|






## Code
- [Explanation Code](https://github.com/Rising-Stars-by-Sunshine/stats201-Eddie-PS-2/blob/main/code/Problem_Set2_Explanation_Eddie.ipynb)
- [Prediction Code](https://github.com/Rising-Stars-by-Sunshine/stats201-Eddie-PS-2/blob/main/code/Problem_Set2_Prediction_Eddie.ipynb)
### Table of Code
| File| Description |
| :---         |     :---:     |
| Problem_Set2_Prediction_Eddie.ipynb  | Code that carries out the prediction task of Problem Set 2 |
| Problem_Set2_Explanation_Eddie.ipynb | Code that carries out the explanation task of Problem Set 2 |

## Spotlight
### Explanation
 ![wordcloud](https://github.com/Rising-Stars-by-Sunshine/stats201-Eddie-PS-2/blob/main/spotlight/figures/wordcloud.png)
 
 Description: This wordcloud figure shows the high frequency phrases used in NFT-related literatures. With the help of natural language processing, it is easy to spot that market, Ethereum, and networks are mentioned more than the other phrases, which can bring insight to research on which of the aspects of NFT is currently focused on.
### Prediction
 **Linear Regression**
 
 ![linear Regression](https://github.com/Rising-Stars-by-Sunshine/stats201-Eddie-PS-2/blob/main/spotlight/figures/linear%20regression.png)
 
  Description: The figure above compares the predicted data and true data using histograms to represent each set's value. We can see that the data overlaps quiet perfectly. The R2 score for the regressor is 0.9915539790301517. Because an R2 score being closer to 1 means the data is better fitted. We can see that the regressor is in high accuracy in predicting the future month's carbon emissions.
  
## References

### Data Source
- [Global Monitoring Laboratory-Carbon Cycle Greenhouse Gases](https://gml.noaa.gov/webdata/ccgg/trends/co2/co2_mm_mlo.txt)
### Code Source
- [stats201-tutorial-prediction](https://github.com/Rising-Stars-by-Sunshine/stats201-tutorial-prediction/tree/main/code)
- [sunshineluyao/design-principle-blockchain](https://github.com/sunshineluyao/design-principle-blockchain/tree/main/code)
### Literature
- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 


- Ante, Lennart. 2021. “Non-Fungible Token (NFT) Markets on the Ethereum Blockchain: Temporal Development, Cointegration and Interrelations.” SSRN Electronic Journal. https://doi.org/10.2139/ssrn.3904683.
- Das, Dipanjan, Priyanka Bose, Nicola Ruaro, Christopher Kruegel, and Giovanni Vigna. 2021. “Understanding Security Issues in the NFT Ecosystem.” ArXiv:2111.08893 [Cs], November. https://arxiv.org/abs/2111.08893.
- Fowler, Allan, and Johanna Pirker. 2021. “Tokenfication - the Potential of Non-Fungible Tokens (NFT) for Game Development.” Extended Abstracts of the 2021 Annual Symposium on Computer-Human Interaction in Play, October. https://doi.org/10.1145/3450337.3483501.
- Ghelani, Diptiben. 2022. “What Is Non-Fungible Token (NFT)? A Short Discussion about NFT Terms Used in NFT.” Authorea. October 4, 2022. https://www.authorea.com/doi/full/10.22541/au.166490992.24247550.
- Hwang, Yohan. 2023. “When Makers Meet the Metaverse: Effects of Creating NFT Metaverse Exhibition in Maker Education.” Computers & Education 194 (March): 104693. https://doi.org/10.1016/j.compedu.2022.104693.
- Kapoor, Arnav, Dipanwita Guhathakurta, Mehul Mathur, Rupanshu Yadav, Manish Gupta, and Ponnurungam Kumaraguru. 2022. “TweetBoost: Influence of Social Media on NFT Valuation.” ArXiv:2201.08373 [Cs], January. https://arxiv.org/abs/2201.08373.
- Mazur, Mieszko. 2021. “Non-Fungible Tokens (NFT). The Analysis of Risk and Return.” SSRN Electronic Journal. https://doi.org/10.2139/ssrn.3953535.
- Muthe, Koushik Bhargav, Khushboo Sharma, and Karthik Epperla Nagendra Sri. 2020. “A Blockchain Based Decentralized Computing and NFT Infrastructure for Game Networks.” 2020 Second International Conference on Blockchain Computing and Applications (BCCA), November. https://doi.org/10.1109/bcca50787.2020.9274085.
- Nadini, Matthieu, Laura Alessandretti, Flavio Di Giacinto, Mauro Martino, Luca Maria Aiello, and Andrea Baronchelli. 2021. “Mapping the NFT Revolution: Market Trends, Trade Networks, and Visual Features.” Scientific Reports 11 (1). https://doi.org/10.1038/s41598-021-00053-8.
- Okonkwo, Ifeanyi E. 2021. “NFT, Copyright; and Intellectual Property Commercialisation.” SSRN Electronic Journal. https://doi.org/10.2139/ssrn.3856154.
- Park, Andrew, Jan Kietzmann, Leyland Pitt, Amir Dabirian, and Amir Dabirian. 2022. “The Evolution of Nonfungible Tokens: Complexity and Novelty of NFT Use-Cases.” IT Professional 24 (1): 9–14. https://doi.org/10.1109/mitp.2021.3136055.
- Pinto-Gutiérrez, Christian, Sandra Gaitán, Diego Jaramillo, and Simón Velasquez. 2022. “The NFT Hype: What Draws Attention to Non-Fungible Tokens?” Mathematics 10 (3): 335. https://doi.org/10.3390/math10030335.
- Popescu, Andrei-Dragos. 2021. “Non-Fungible Tokens (NFT) - Innovation beyond the Craze.” ResearchGate. unknown. August 18, 2021. https://www.researchgate.net/publication/353973149_Non-Fungible_Tokens_NFT_-_Innovation_beyond_the_craze.
- Vasan, Kishore, Milán Janosov, and Albert-László Barabási. 2022. “Quantifying NFT-Driven Networks in Crypto Art.” Scientific Reports 12 (1). https://doi.org/10.1038/s41598-022-05146-6.
- Wachter, Victor von, Johannes Rude Jensen, Ferdinand Regner, and Omri Ross. 2021. “NFT Wash Trading: Quantifying Suspicious Behaviour in NFT Markets.” SSRN Electronic Journal. https://doi.org/10.2139/ssrn.4037143.
- Wang, Qin, Rujia Li, Qi Wang, and Shiping Chen. 2021. “(PDF) Non-Fungible Token (NFT): Overview, Evaluation, Opportunities and Challenges.” ResearchGate. May 2021. https://www.researchgate.net/publication/351656444_Non-Fungible_Token_NFT_Overview_Evaluation_Opportunities_and_Challenges.

