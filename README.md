# Pacmann Academy - Machine Learning 01 : Fare Amount Prediction
**Note:**
- This dataset originally comes from [Uber Fares Dataset](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset)
- Full Code: [Full Python Code - Fare Amount Prediction](https://github.com/oktaviorezap/fare-amount-ml01-pacmann-academy/blob/main/Mentoring_01_Introduction_to_Machine_Learning_Sekolah_Data_(Oktavio_Reza_Putra_JPP_MAX_Pacmann_Academy).ipynb)

<br>

**Task Description:**
- We're looking to predict the fare of Uber's transactions.
- The dataset contains of the following fields

<center>

|Feature|Type|Descriptions|
|:--|:--|:--|
|`order_id`| `int` | a unique identifier for each trip|
|`pickup_time` | `str` | a class of pickup time. `04-10`, `10-16`, `16-22`, `22-04`. E.g. `04-10` means the pickup time is between 04.00 to 10.00|
| `pickup_longitude` | `float` | the longitude where the meter was engaged|
| `pickup_latitude` | `float` | the latitude where the meter was engaged|
| `dropoff_longitude` | `float` | the longitude where the meter was disengaged|
| `dropoff_latitude` | `float` | the latitude where the meter was disengaged|
| `passenger_count` | `float` | the number of passengers in the vehicle (driver entered value)|
| `fare_amount` | `int` | the cost of each trip in USD, (**our target**)|
