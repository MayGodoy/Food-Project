# Food-Project 🌯🥘🍝🍜🍣🥟
 
 The food project is a project based in NLP. It's one of the project I did in my training as data Scientist. 
 
 *Business case: There will be a foodie fair in your city next summer, and the organsers have contacted us because they are interested in performing an analysis of the world wide cuisines. They manage to obtain a dataset from different cuisines all over the world, together with the list of the most common ingredients. Some of our strongest geographic and cultural associations are tied to a region's local foods, so they are interested to know more information regarding them in order to organise the different stands. People from Marketing have ideas on how to plan the fair but they want to complement their ideas with some rough results.*


The goal of the project is to give the most different types of cuisines.  For that, I need to know the data. 


### The Dataset

The dataset has almost 40 K of recipes (exactly 39774) divided into three columns: the id, the type of cuisine, and the ingredients.

It contains 20 different types of cuisine: 
Italian 7.8 K, Mexican 6.4 K, southern_us 4.3 K, Indian 3 K, Chinese 2.6 K, French 2.6 K, cajun_creole 1.5 K, Thai 1.5 K, Japanese 1.4 K, greek 1.1 K, Spanish 989,  Korean 830,  Vietnamese 825, Moroccan 821, British 804, Filipino 755, Irish 667, Jamaican 526,  Russian 489, Brazilian 467.

![cuisine_distribution](https://user-images.githubusercontent.com/58269063/150573616-106d9675-96dc-4438-9543-de8cfa9ebd86.png)


And the length of the recipes has a large width. In the graph, You can see the skewness. 
And the concentration is between 4 and 20 ingredients. I reduced the data to select only the recipes to 5 to 19 ingredients because a recipe with 20 ingredients is not viable in a fair


![lenght_distribution](https://user-images.githubusercontent.com/58269063/150573582-25cecfad-81f4-44ad-8e5c-f77fb60d7d65.png)



And after generating the length I generated a new column with recipes with meat and without meat to add a new filter. 
And there are the distribution according type of cuisine with and without meat.

![Meats_distribution](https://user-images.githubusercontent.com/58269063/150573542-79e0bbe6-49bf-4692-99c3-efe1e78ac30f.png)
![NoMeats_distribution](https://user-images.githubusercontent.com/58269063/150573545-5c25719b-6dc2-4017-9b42-d66d927d37ba.png)



There are the more frecuent meats 

![Meats](https://user-images.githubusercontent.com/58269063/150573652-020a5a87-cf57-4b85-9a17-47f2ccf806fa.png)

