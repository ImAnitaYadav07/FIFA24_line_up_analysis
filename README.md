# FIFA22 Qater Exploratory data analysis

## Background</a>

The FIFA World Cup: a stage for legendary triumphs, unexpected upsets, and the pulse of global football. It's a saga etched in history, a tale told through data. Our mission? To unearth the hidden stories and pivotal moments that define the World Cup's rich heritage.

In this data analysis odyssey, we journey through World Cup history's statistical maze. From the mesmerizing goals to the epic showdowns, we unravel the secrets that forged the legends and sparked the underdog uprisings.

<div class="alert alert-block alert-info",style="font-size:14px; line-height: 1.7em">
<p>🎯 <b>Goals</b>:
<li>Analysing the FIFA historic data from 1872 to 2023 </li>
<li>Analysing the National Team, Players, and Results</li>
<li>Analysing the win and losing match distribution of each national team</li>
<li>Analysing the Each team and player performance and goals distribution. </li>
</p>
<br>
<p>🔨 <b>Tools</b>:
<li><i>numpy</i> and <i>pandas</i> for data manipulation</li>
<li><i>missingno</i> to display the missing data in the FIFA-result and FIFA-goalscore dataset</li>
<li><i>seaborn</i>,matplotlib and <i>plotly</i> for data visualization</li>
</p>
</div>

## <a id='1'>Dataset</a>

* result dataset - [result.csv](international-football-results-from-1872-to-2017/results.csv')
![data-preview](https://github.com/ImAnitaYadav07/FIFA24_line_up_analysis/blob/127ad3116bfce75a5758cc99f4ee7db37130fc10/dt.png)
* goalscore dataset - [goalscore.csv](international-football-results-from-1872-to-2017/goalscore.csv') 

## <a id='1'>Data Wrangling</a>

```
   data.isna().sum()
```

```
   data.duplicated().sum()
```

```
   data.dropna()
```

```
   data.drop_duplicates()
```

## <a id='1'>Explorotory Data Analysis</a>

* In which month most matches are played ?
```
   In june(6744) month most matches are played.
```
![data-preview](https://github.com/ImAnitaYadav07/FIFA24_line_up_analysis/blob/e1743724de1f9db890280946e1bd8ae85531ebb2/weekmonth.png)

* On which weekdays most matches are played ?
```
  On Wednesday(10.343k) and Sunday(10.747k) most matches are played.
```
![data-preview](https://github.com/ImAnitaYadav07/FIFA24_line_up_analysis/blob/127ad3116bfce75a5758cc99f4ee7db37130fc10/weekm.png)
* Does home advantage helps a team to win ?
```
   From the above plots if we only see the win count in false(not a neutral venue or home ground) and true(neutral ground)
    then there is home advantage as in false(win is around 17K) and in true(win = 4807).
```
![data-preview](https://github.com/ImAnitaYadav07/FIFA24_line_up_analysis/blob/127ad3116bfce75a5758cc99f4ee7db37130fc10/weekday.png)
* Number of matches played in tournaments each year ?
```
   There are 609 FIFA World Cup qualification matches played in 2021 highest till now. It is followed by 491 FIFA World Cup
    qualification matches in 2001 played and then 426 Friendly matches played in 2018.
```
![data-preview](https://github.com/ImAnitaYadav07/FIFA24_line_up_analysis/blob/127ad3116bfce75a5758cc99f4ee7db37130fc10/topteam.png)
* Who is the best team of all time ?
```
   By comapring the top 5 home teams and away teams we can say that Brazil has won most number of home matches.
```
* Which teams dominated different eras of football ?
```
   19s era(or from 1900-2000) Brazil(298) grabbed the top spot followed by Argentina , Sweden , Germany. Many legends
     played in that era.
```
![data-preview](https://github.com/ImAnitaYadav07/FIFA24_line_up_analysis/blob/127ad3116bfce75a5758cc99f4ee7db37130fc10/topplyer.png)

* What countries play with each other the most ?
```
   Argentina and Uruguay have grabbed the 1st spot with 179 total matches together followed
   by Austria and Hungry with 137 matches together.
```
* Which countries host the most matches where they themselves are not participating in ?
```
   USA has hosted 894 matches in which it not participated. It is followed
   by Malaysia(473 matches) and Quatar(372 matches).
```
![data-preview](https://github.com/ImAnitaYadav07/FIFA24_line_up_analysis/blob/127ad3116bfce75a5758cc99f4ee7db37130fc10/playergoal.png)
* Which teams are the most active in playing friendlies and friendly tournaments ?
  
```
   Austria and Hungary have played most friendly matches together 115 matches
   followed by Netherlands and Belgium 109 matches.
```

* Which player score the most goals ?
```
   Cristiano Ronaldo scored most goals(91) and has a average goal scoring time
   of 54 min(or mostly scores in 2nd half of the game).
```
* Which player has scored more goals in penalty ?
```
   Again 1st spot is taken by Cristiano Ronaldo scored 16 penalty goals
   followed by Lionel Messi - 14 goals and Hristo Stoichkov - 13 goals.
```
* which teams scored their own goals ?
```
   Germany has most own goals(4) followed by Russia,Crotia,Mexico,Spain,Canada.
```
![data-preview](https://github.com/ImAnitaYadav07/FIFA24_line_up_analysis/blob/127ad3116bfce75a5758cc99f4ee7db37130fc10/teamgoal.png)

* Which team score most goals in 1st half or second half ?
```
   Top 5 spots shows that Brazil,Germany,Argentina,Spain,Netherlands had scored most goals in 2nd half
    of the match because there are often player replacement or change of playing technique or goal chasing after the 1st half.
```
![data-preview](https://github.com/ImAnitaYadav07/FIFA24_line_up_analysis/blob/127ad3116bfce75a5758cc99f4ee7db37130fc10/secondhalf.png)

* Which player score most goals in 1st half or second half ?
```
   Cristanio Ronaldo is on 1st place and he mostly goals in second half.He is followed by Ali Daei and Robert Lewandowski.
```
![data-preview](https://github.com/ImAnitaYadav07/FIFA24_line_up_analysis/blob/127ad3116bfce75a5758cc99f4ee7db37130fc10/firsthalf.png)

###  Credit to-

* for dataset - kaggle
* for analysis refernce & guidence - NISHCHAY SINGH @kaggle

      

