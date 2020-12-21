# Lab 5 – Refugee Stats using Dictionaries

In this lab, we used populations of refugee camps from five different countries to find the total number of refugees in those countries in 2014.  The source of this data was the UN Refugee Agency, accessed from https://en.wikipedia.org/wiki/Refugee_camp.  From this data, a dictionary with country and refugee population as the key and value pair was created. This dictionary was used to print a series of outputs: country names, total refugee population values, and statements saying how many refugees are in the country.

## The Code

Prior to creating functions to print country and refugee information; the data is assigned to variables and a dictionary is created:

1. The five countries of interest, Kenya, Jordan, India, Ethiopia, and Djibouti, are put in a list.
2. Lists for each of these countries containing the refugee population of each camp is put into lists.  
    e.g. KenyaCamps_2014pop = [153959, 106968, 88486, 83750, 52310, 21035]
3. A blank list is created to hold to total refugee population for each country.
4. A function is then created to sum all refugee camp populations within individual countries and append the total to the blank list.
5. This function is called with each country's refugee camp population list in the order of the country list.
6. The dictionary is then created combining the country name and the total refugee population as the key and value.

### Function 1--Print country names contained in dictionary:

1. A function is created that prints all country names in the key, value pair of the dictionary.
2. The dictionary is looped through and prints the key (country) of each pair within the dictionary items.
3. The function is called with the dictionary that was created prior which outputs the 5 country names.

### Function 2--Print refugee populations contained in dictionary:

1. A function is created that prints the refugee populations for all five refugee populations in the key, value pair of the dictionary.
2. The dictionary is looped through and prints the value (refugee population) of each pair within the dictionary items.
3. The function is called with the dictionary that was created previously which outputs the 5 refugee populations.

### Function 3--Print statement "*COUNTRY* had *VALUE* refugees in *YEAR*." :

1. A function is created that prints a series of statements telling how many refugees are in each of the 5 countries.
2. The dictionary is looped through and for each key (country), value (refugee population) pair, a statement is printed.

    e.g. "Kenya had 506508 refugees in 2014."
3. The function is called with the dictionary that was created previously and the 5 print statements are outputted.

## Issues

I had difficulties creating the dictionary without simply calculating the totals outside of Python and creating a dictionary that way.  In this method, the refugee camp population lists must be called in the order of the country list when running the sum function.  Otherwise, the values will not be assigned to the correct key.




