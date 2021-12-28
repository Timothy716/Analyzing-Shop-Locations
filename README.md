# Analyzing-Shop-Locations
Finding the Perfect Location for a new Restaurant.

**Introduction

Hamburg is one of the biggest cities in Germany with about 1.84 million inhabitants. Those big cities are well known for their always changing streetscape. One part of this are the coffee shops and restaurants. In fact, many of these shops failed to stay longer than a year. The reason for that is that there are several factors that are not well handled before opening such a shop. One factor which is of outmost importance for the success is the location. In order to find the right location, the neighbourhood has to be well analysed. But as mentioned before big cities are known for their fast-changing streetscape. Additionally, if somebody is not a local it is even harder to find the perfect location. This situation could occur when for example a franchise from München wants to have some shops in another city. Therefore, it is not easy to have a sufficient overview in an appropriate time. This report shows a method to analyse neighbourhoods with special focus on restaurants and coffee shops. This leads to the question: Where should a restaurant or a coffee shop open? The hidden question behind this is: What kind of restaurants should be opened? Are there differences between the location of fast-food restaurants and other restaurants? 
The data of the Foursquare database should be used to give information to answer those questions. 

**Description of the Data

The used come from the Foursquare database. This database provides a variety of information’s about venues and also has data about user evaluations with sometimes written feedback. The stored information in the database is sufficient to answer the question. First of all, it should be defined what information we need to answer the question. Obviously, some information’s about the location and type of restaurant are needed. If it is available, the rating of those restaurants or coffee shops should be stored. This will be done by sending a get request to the API of Foursquare. In order to have access to the database an account has to be created and the credentials have to be put into the request. Furthermore, the search query has to be defined. It seems to be simple, but some thoughts have to be put into it. For example, leads the search for restaurants not to the same result as the search for food. This is because they are separated into different categories and therefore will not show up in the same search query. Also, the search for burger and restaurants will not have the same result. In fact, this can be helpful to answer the given questions. 
The following figure shows a first overview of the city. The only information that the investor has to give is a starting point and the radius around this point. The starting point in this case is the central station in Hamburg. 

 
Figure 1: Overview 

![image](https://user-images.githubusercontent.com/75427181/147578788-34b5288b-f9b3-4813-9340-9f22f35d828d.png)

Those kinds of graphical presentation will be used to answer the question. It is simple to derive some insights by going over Figure 1.

**Methodology 

In order to find a decent answer for the given questions it is important to specify the main idea. The best way to understand where the best location is, is to understand where the current competitors are. The underlying concept is that if somebody wants to eat something special, he will remember places where he went before to eat that kind of food. For example, a person wants to eat a pizza. If the new store is next to the store the person is looking for it could happen that he is interested in the new shop and wants to try it. Therefore, a lot of advertisement cost could be saved and in case the food in the new restaurant is better a permeant customer could be won. From this it is concluded that there is the need to know where the current restaurant and coffee shops are. In order to understand where the currents shops are the following figure will be introduced. 
 
![image](https://user-images.githubusercontent.com/75427181/147578815-8d54e9df-8c1b-4dab-a35d-86b90358ebf4.png)

Figure 2: Overview of all kinds of restaurants and coffee shops in the region

It can be seen that there several fast-food restaurants in the west of the central station. Additionally, it can be predicted that there are a lot of coffee shops. Taking a view in the east side of the central station it can be derived that there are less fast-food restaurants and also not so many coffee shops compared to the west. But the numbers of restaurants in this area are higher than in the west. In fact, there is a street with almost seven restaurants close together. It seems like a food passage. 
In order to take a closer look at the rent price structure in this are the following figure is used. This Figure was taken from a reliable resource form the internet. The exact link can be found in the literature section below.

![image](https://user-images.githubusercontent.com/75427181/147578869-d765d1b8-bac3-4a28-8e5a-c3c392aaf3fb.png)

Figure 3: Rent index in Hamburg [1]
It can be predicted that the cost increases the closer the estate is to the Alster. Besides from this fact the price structure seems to be the same. There are some expensive and a view middle- and low-class estates. 

**Results

In the west of the central station are a lot of shopping opportunities. Therefore, the people in this area are interested in buying clothes and other consume products. They are less interested in staying at one place and eat in peace. They want to hunt for the next sale. If they are hungry or need some energy, they are more interested in drinking a cup of coffee or eating fast-food. Therefore, this area is not the right place to open up a restaurant. 
In the east of the central station are not that much consume shops. Of course, they are some places to buy products, but those places are specialised small and expensive shops. Additionally, there is a lot of working people they want to eat lunch in their break. The people have more time or just want to take some time to eat and talk to their colleges and friends. 

**Recommendations

If the investor is interested in opening a fast-food store or a coffee shop this is the right place to be. Because of the high rent prices, it is recommended to place it in the south west of the central station. According to Figure 3 the rent prices are lower than near the Alster and the products could be given to a smaller price.
As said before is the east the best place to open up a restaurant. Here it is recommended to open up a restaurant in the food street that was detected in the section before. Furthermore, the restaurant should be at the beginning of this street. Otherwise, the situation could occur that hungry customers never go far enough to see the new restaurant. 

**Conclusion

It is all about what is the customer interested in and how much time did he want to spend with it. This analysis of the food and coffee stores near the central station is a good example to understand the statement above. People that are hunting for sales have not much time to eat and relax. They are in the hurry and want to spend their time in dressing rooms not in restaurants. On the other side, in this example the other side of the central station. People would like to take their time to sit down and eat something. Maybe have a conversation with their colleges in their break or are just enjoying a good meal. During this analysis the question that are asked in the first section could be answered and an approach to analysis neighbourhoods could be derived. The beauty of it is that not complex statistics or machine learning has to be used. Therefore, this approach is adaptable to different cities in minutes. 


**Resources

[1]https://www.homeday.de/de/preisatlas/hamburg/eimsbuetteler+chaussee+98,+20259?map_layer=standard&marketing_type=rent&property_type=apartment&embed&utm_medium=partner&utm_source=wohnungsboerse (last visited 13.04.2021).
