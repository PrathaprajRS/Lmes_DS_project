Readme project file for train accidents in India

Step A:

1. creating a data set
	a. create a google form for data entry
	b. data entered from Jan 1970 t0 Aug 2024
	note:-
	  > filling data in google form looks time consuming process
	  > so coping data to google sheet and pre processing it for making a dataset
2. reference taken from Wikipedia link - 
 	https://en.wikipedia.org/wiki/List_of_railway_accidents_and_incidents_in_India

Step B:

1. Creating columns for dataset preparation
  a. accident_date and time
  b. train_name 1 & 2 
	note:
	 1.need of 2 names if collision occurred 
	 2.need of 1 name if derailment or sabotage occured 
  c. category_of_train - 
		express
		mail
		superfast
		freight
		passenger
		vande_bharath
		suburban_train
		metro_train
  d. death_fatalities
  e. injuries
  f. type_of_accident 
		technical(collision,derailment)
		non-technical(sabotage,cyclone)
  g. cause_of_accident 
		collision
		collision on an obstacle
		derailment
		derailment and collision
		sabotage
		tropical cyclone derailment
		climate condition like fog rain   	
  h. compensation_for_death
  i. compensation_for_injuries
  j. location_of_accident_place
  k. location_of_accident_state
  l. zone of accident occurred

	note:-
	   > by studying the Wikipedia page creating 7 possible columns
	     like Date, Type of Accident, Type of Train, Deaths, Injuries,
	     Category of Accident(tech or non tech), Zone of Accident occurred


Final requirement of columns can create in excel
	1. Date
	2. category of accident - technical or non technical
	2. type of accident - collision, collision on an obstacle, derailment, derailment and collision, sabotage, tropical cyclone derailment, climate condition like fog rain, 
	3. type of train (train 1, train 2, train 3) - 3 column
	4. death
	5. injuries
	6. full details of accident 
	





2. Cleaning and Preprocessing of dataset
  a. shape of dataset
  b. describe dataset
  c. handling missing values
  e. feature engineering 
	- create new columns using existing ones to improve model performance
  f. data transformation
  	- fit and transform (scale/normalize data),encode categorical variables

3. Data Analysis and Visualization
   a. EDA - exploratory data analysis
   b. visualization
	
4. Train data and creating ML model algorithm(Model training)
   a. train models - use scikit-learn

5. Metrics (Evaluate the accuracy)
   a. evaluate models 
	- use metrics (e.g., accuracy, RMSE, F1-score) to compare models.

6. Model Optimization
   a. hyperparameter tuning
	- use techniques like Grid Search or Random Search 
	  to find the best model parameters.
   b. ensemble methods
	- random forest (combine multiple models 
	  to improve performance from decision tree)