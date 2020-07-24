# Panda-List
Data Vault Manager

* I have been deployed as a data vault manager. As part of my assignment, I was required to create a Pandas data list.
* Using Python pandas i created a list of Dataframes for the   following products:


1. Chips: Simba, Lays
2. Cooldrinks: Coke, Fanta
3. Chocolates: Cadbury, Tex
4. Pies: Pepper Steak, Chicken
5. Fruit: Pear, Apple, Orange
6. Cupcakes: vanilla, chocolate
7. Veggies: spinach, cabbage
* I have been deployed as a Data Scientist. As part of your assignment, i am required to:

1. Create a Mongo Database and name it Data Tracker.
2. Add my SPRINT 3 products file to MongoDB i just created.
3. Create a collection for my top 3 products in MongoDB.
4. Insert multiple documents into my collections in question (3)
5. Implement a descending sort to my data in MongoDB.
6. Delete 2 brands from my collection of top 3 products.
7. Update 1 product and its brands from the collection i created in question (3).
8. Track (Search/Filter) for the least 5 brands in my products.
9. Save my MongoDB data and code to GitHub

## Description of coding practices

  1. To start of, import the pandas as pd (Module). (depending on your IDE you may have to install panda first befor importing the module)

  2. Create dataframe and store values. 

  3. During the code i had the following error: "ValueError: arrays must all be same length"
       - What this means is that the values stored must be of the same length. 
         If you note in the above we have 7 Values, 6 of those values have two products/ arrays only one has three.
         Now what we have to do is to create empty strings to the rown that has two products. This should then make your arrays be of same length.

  4. Be sure you have Pands installed in your IDE or you will receive error "ModuleNotFoundError: No module named 'Pandas' " when importing pandas
      The following IDE comes with pands package when installed
  

      
## Technologies 
 Python
 
 # IDE:
 Anaconda3: Jupyter Notebook 6.0.3
 
 Author: Zama Zaid Ndabeni
 (intern Capaciti Tech)
 Interncptwex070@capaciti.org.za 
