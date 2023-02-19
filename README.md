# Prediction of Monthly Carbon Emissions
## Project information
- **Author**: Eddie Lin, Computation and Design major Computer Science track, 2025, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**:  Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: Thanks to Prof. Luyao for insightful comments in improving the research question and the inspiring lectures, special thanks to my classmates for the interesting discussions in class.
- **Project Summary**: 
  - [Summarize the Background/Motivation]
  - [Research Questions]
  - [Application Scenario (Data Source)]
  - [Methodology]
  - [Results]
  - [Intellectual Merits and Practical impacts of your project.]

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
### Prediction
 **Linear Regression**
 
 ![linear Regression](https://github.com/Rising-Stars-by-Sunshine/stats201-Eddie-PS-2/blob/main/spotlight/figures/linear%20regression.png)
 
 **Random Forest Regressor**
 
 ![random forest regression](https://github.com/Rising-Stars-by-Sunshine/stats201-Eddie-PS-2/blob/main/spotlight/figures/random%20forest.png)
## More about the Author
- headshot
- self-introduction
- Final reflections 

[how to apply a various machine learning methods to solve social science issues?]

## References

### Data Source
- Data Source Title and URL
### Code Source
- Code Source Title and URL
### Articles
- Article Source Title and URL
### Literature
- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

```
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
```

