# Shakespearslines
#### Project2 for EECS 731
Shakespear play dataset was downloaded from https://www.kaggle.com/kingburrito666/shakespeare-plays <br>

The project includes following procedures: <br>
  * Load the data set into panda data frames and get info of players and plays
  * Using `Network Analysis` to establish additional value `Centrality degree` of all players
  * Generate dataset for regression from string data:
    > Extract analyzalbe data from lines: count number of characters and words for each line <br>
    > Replace play name and players with label
  * Build classification models to determine the player 
    > Using the other columns includes 'Play''PlayerLineNumber''Act''Scene''LIne''Num of letters''Num of words' as features <br>
    > Applying `Decision Tree` and `Random Forest` for classification <br>
    > Set different numbers of estimators for comparision

Conclusion: 
   * Both method provides a desirable result for this classification problem: testing score > 82%
   * Random Forest(88.3%) performs better than Decision Tree(82.3%) in this case
   * A larger estimator set would improves accuracy
