# Billboard Hot 100 Analysis
### An analysis of Billboard Hot 100 entries and using machine learning to predict a song's peak position

### Table of contents
- [Description](#description)
- [Visualisations](#Visualisations)
- [Author Info](#author-info)

---
## Description
This project uses a database of all Hot 100 entries from github (https://github.com/HipsterVizNinja/random-data/tree/main/Music/hot-100) since records began to find patterns in the data. Other data on the song is then extracted using Spotify's API to perform machine learning on the data.

### Technologies and packages used:
- Python
  - *pandas*
  
    Used to clean the data
  - *spotiPy*
  
    Used to add more data on genre, song length etc
  - *numPy*
  
    Used in the machine learning
  -Scikit-learn
  
    Used to perform machine learning
  - *seaborn* and *matplotlib*
    
    Used to visualise the machine learning predictions

- Power BI

- Tableau

[Back To The Top](#Billboard-Hot-100-Analysis)
---
## Visualisations

The following visualisations were created with the cleaned data from all charts.

This shows the average time a song is in the charts based on where the song debuts.

![image](https://user-images.githubusercontent.com/116348107/213723920-4967210d-9bc2-43fa-94b8-00e911774d61.png)

This shows the number of songs individual artists have had that debuted at number 1. This visualisation is relevant to the machine learning as it indicates that the artist could be an important feature determining the peak position.

![image](https://user-images.githubusercontent.com/116348107/213724134-75081302-52cf-4b47-8468-fd950251c7b9.png)

This visualisation shows the genres that have the most number 1s. Similarly to above, this shows genre could be important in predicting a song's peak position.

![image](https://user-images.githubusercontent.com/116348107/213724428-fb913feb-c837-4ca3-92f4-edf08d88be4e.png)

The following visualisation shows the actual peak position of a song agains the value predicted using ridge regression. This shows that regression models may not predict peak position well as multiple songs are predicted below 0 which is impossible.

![image](https://user-images.githubusercontent.com/116348107/213724619-ee790260-d154-40f6-a767-ebed47db0777.png)

The final visualisation shows the feature importances after using decision tree classification. Classification was used to predict if a song debuts in the top 25 of not. As shown in a previous visualisation, the artist is a fairly important feature for this prediction.

![image](https://user-images.githubusercontent.com/116348107/213724956-71d7ecc4-3125-4e2a-a15f-d58c83bda254.png)

[Back To The Top](#Billboard-Hot-100-Analysis)
---
## Author Info

LinkedIn - [Jasmine Albert](https://www.linkedin.com/in/jasmine-albert-99029b207/)

[Back To The Top](#Billboard-Hot-100-Analysis)
