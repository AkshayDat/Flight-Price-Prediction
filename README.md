# Flight-Price-Prediction

# Problem Statement

Anyone who has booked a flight ticket knows how unexpectedly the prices vary. Airlines use using sophisticated quasi-academic tactics which they call "revenue management" or 
"yield management". The cheapest available ticket on a given flight gets more and less expensive over time. This usually happens as an attempt to maximize revenue based on -

Time of purchase patterns (making sure last-minute purchases are expensive)
Keeping the flight as full as they want it (raising prices on a flight which is filling up in order to reduce sales and hold back inventory for those expensive last-minute 
expensive purchases)

# EDA Concluding Remarks


![image](https://user-images.githubusercontent.com/67465039/115984533-29998780-a5c5-11eb-97ef-aa0388f7e326.png))


The above barplot shows the price of traveling through each airlines the price hike of jet airways is maximum as they provide good service with comfort.


![image](https://user-images.githubusercontent.com/67465039/115984630-ccea9c80-a5c5-11eb-9107-b1d7f5118bb8.png)


The above barplot shows that the flight with maximum number of stopages has higher price.



The datasets contains 1 null value in the Additional Information column after removing it there was no null value present in the datasets.

Jet airways airlines has more number of flights and  Indigo airlines is on second number.

There were outliers present in some of the columns  such as : Airlines, and price columns.

Route is positively corelated with Journey Mont column.

price column is highly negatively corelated with the Total_Stops column, and is positively corelated with the duration column


# Result

The Random Forest regressor and the GradientBoostingRegressor are giving the good accuracy.



