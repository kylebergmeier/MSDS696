# MSDS696
In this project I developed a model to preoject the number of wins a college football team had in 2022. Data was collected from a Kaggle source that had a comprehensive list of the statistics the teams produced over the course of the season. The features were then run through many tests to determine which of them would do the best job in projecting the win total.

![Def_Heatmap](https://github.com/user-attachments/assets/f0db8f63-ff25-4dbc-b437-6b4e02a80fbf)
![Off_Heatmap](https://github.com/user-attachments/assets/3e3d0338-e346-452b-8408-360e18c2e307)

# Model Construction
A few different models were used and tested to decipher which of the selected choices would perfrom the best. I also sought out to test how it would work if I were to pick the features I felt were important vs what seemed to correlate the best vs the whole dataset. Ultimately, RF models seemed to have a slight edge over the other models but only left us with a r^2 of 0.81 when it was all said and done. The MSE and MAE were also a little higher than we would have wanted but the variance is so high that it meant that the model still did a decent job at showcasing the results. 

![Residuals](https://github.com/user-attachments/assets/6a3c957d-fb15-42e2-99f9-1067a2f35e4b)
![Wins_Graph](https://github.com/user-attachments/assets/92374b0c-8717-4a24-92a1-618130c842fb)

# Future Work
I want to now try and begin to push this into the forward thinking world. Obviously, that would take a lot more data from different sources but I think it would be interesting to take a look at. I am also interested in looking into other model types to see if the perform any better.
