# Data Sciences Test

### QUESTION 1
The first generation pokemon database is provided in a MongoDB instance. These are the details: 

- DB Name: pokemonsample
- DB Collection: samples_pokemon
- A pokemon can have evolutions

Questions: 

1) You should provide for all the pokemon that have 1 or more evolutions the name, number and spawn time of the evolutions. Estimated time: 15-30 minutes. 

2) All first evolution pokemon that have an evolution with an avg spawn greater than 4 (the evolution should have the avg spawn greater than 4, not the initial pokemon), you need the name and number of each pokemon that meets the following requirements. Estimated time: 1-2h

If you find a solution send the query for each question and its result, otherwise send the reasoning or the query in pseudocode.

Connection URL:

	mongodb+srv://testUser:testUser123@cluster0.repty.mongodb.net/pokemonsample?retryWrites=true&w=majority

Recommended tools: Robo 3T // Studio 3T


### QUESTION 2
In TPMBA we consider "Finisher" to a student who has finished the master. In the email are attached two files, the first one called "UsuariosDF" which includes the list of all the students we have on the platform, and the second one called "FinishersDF", which is the same but filtering only by the users who are finishers. The explanation of the columns is as follows: 

- **userstatuses.user** → Fictitious user identifier
- **promotions.type** → Promotion in which the user participates
- **promotions.name** → Promotion Name
- **promotions._id** → Fictitious promotion identifier
- **promotions.startDate** → Promotion Starting Date
- **promotions.monthsLeft** → Months the promotion lasts
- **Country** → Country from which the program was purchased
- **Program_price** → Money we have generated for each program sold


Promotions have a limited duration. To calculate the end time of the promotion, you would have to take the start date "startDate" and add the remaining months to it. Therefore, a promotion that starts on the 1st of March of 2019, and lasts 13 months will end in April 2020. 

Taking these considerations into account, would you be able to answer these questions? For this exercise, it is necessary to attach both the result in a CSV file and the jupyter notebook used to solve it as the result. As a recommendation, make a first data analysis as some data transformations might be needed. 


1) How many users are from Spain?  
  
2) Can we know the amount of money in dollars that we have invoiced? What is the average? In case there is no price in the program, we will take 499.99€ as the default value. Take also the “promotions.startDate” field as the purchase date of the program. To convert from Euros to Dollars, take a look at the "historico.csv" file, where the conversion rate since 2019 appears.  

3) Can you make a chart showing how many finishers there are for each promotion? The promotion to which a student belongs is indicated by the "promotions.type" column. For example:
  - Promotion: thepowermba → 9K finishers
  - Promotion: powerjob → 1K finishers
  - ...


4) Can you send this data to a MongoDB database? 


