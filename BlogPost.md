---
title: 'The Flight of Gulls: Nico, Eric & Sanne'
author: "Aldric Martinez-Olson, Augusta Fricke, Carolina Lopez"
output: 
  html_document:
    keep_md: TRUE
    toc: TRUE
    toc_float: TRUE
    df_print: paged
    code_download: true
---
<center>![](seagull-sunset-gravityx-designs.PNG)</center>









## Introduction
![](purpledots.PNG)

The seagull swoops down gracefully, breaking the surface of the water with its beak. It catches a small fish and settles down on a bank to eat its meal. Today, the seagull did not have to travel far for its meal. As the months get colder, it will have to make a long journey so that it can survive.

Most species of seagulls are migratory birds. They change locations based on temperature, breeding season, and food scarcity. Two organizations, LifeWatch and Flanders Marine Institute, worked together to collect data on the flights of three Lesser Black-backed Gulls. Lightweight, solar powered GPS devices were attached to the bird’s ankles that recorded data for almost two years. For detailed information about the dataset and how studies were conducted, visit Open Science Lab for Biodiversity’s website [here](https://oscibio.inbo.be/blog/bird-tracking-data-published/).

The data collected spans from August 2013 to April 2014 and covers countries along the outer coast of Eastern Europe and Northeastern Africa. The depth of information on their flight data allows us to ask some key questions. Did these three seagull’s travel together when migrating or do their flight patterns differ drastically? As for the flight itself, what is a common speed and altitude for traveling seagulls?

It is important to note that seagulls stay close to water sources, as they are primarily omnivorous. Their diet includes a wide variety of fish, insects, mollusks, crustaceans, marine worms, small birds, nestlings, eggs, rodents. They also eat plants such as berries, seeds, and seaweed. If necessary, they scavenge for refuse around garbage dumps.


## Flight Path 
![](orangedots.PNG)

The gulls’ data set begins with them dwelling for the summer in Northern France. European Lesser Black-backed gulls begin their mating season in early summer, and it then takes about a two months for the chicks to fledge. Sanne, likely the female gull (although not specified in the metadata), spent her summer in Somme, France - as did Eric. Nico spent the summer months in between Pas de Calais, Aisne, and part of Belgium. Although, little can be speculated about the time the gulls spent in these months it is interesting to note that Sanne (pink) took off for the western coast in early September, two months earlier than Nico and Eric. Nico and Eric leave for the coast in November. Perhaps the male birds remained longer in their colonies in order to defend their territory, or because their food source was still stable.






![](FRANCE_gif.gif)<!-- -->

Here is a map of the year-long flight paths of the three birds.





![](WHOLEFLIGHT_gif.gif)<!-- -->


Several calculations were made in order to determine the months that the gulls traveled the most and the least:

Eric traveled the least in February, Nico in August, and Sanne in November.
Eric and Nico traveled the most in April and November. Sanne in April and September.
It is interesting to note that the months they traveled the least are all in different seasons. This likely has to do with the abundance of food available to them and their colonies, as well as the gender differences.





## Flight Altitude
![](rosedots.PNG)
The three seagulls had different average flight altitudes over the course of 2013. Nico’s average altitude was 67.9 ft, Eric’s average altitude was 60.2 ft, and Sanne’s average altitude was 29.2 ft. Sanne’s average altitude is lower than the other two because she flew below 0 ft more often than Nico and Eric. Altitude can be negative because it is a measurement of location relative to the horizon. Birds can fly below 0 ft because landscapes vary in altitude and can have dips. Eric’s average altitude is between Nico and Sanne’s so we have chosen to display  Eric’s flight paths.





Eric’s altitude during the first week of January was between -246 ft and 92 ft. His flight pattern shows that he flies at a low altitude when he heads towards a destination at sea. He then returns to land at a higher flight altitude. This makes sense because sea levels are lower than land and there are less obstacles to fly over. His altitude patterns may be a tool to conserve energy.







![](EricAltJan.gif)<!-- -->


Eric’s altitude in the first week of March was between -438 ft and 317 ft. This range is much broader than the altitudes flown at in the first week of January. Gulls fly at higher altitudes in warmer months since the prevailing winds are picking up in force. Bird’s use the strength of prevailing winds to save energy as the months get warmer. Compared to January, Eric is not traveling out to sea as much and when he does, it is not as far of a distance. This could indicate that Eric is traveling for a food source that becomes easier to catch in warmer weather, such as fish.






![](EricAltMarch.gif)<!-- -->

## Flight Speed
![](yellowdots.PNG)
To draw conclusions about the gulls’ flight speeds we have created a data visualization for Sanne.  Sanne stays in Senegal during the colder months of the year. The area of Senegal where she stays is a dry, tropical, and sparsely populated habitat  - an ideal destination for Sanne to escape the cold and busy towns of Northern France where she stays during the rest of the year.





![](SanneFlightJan.gif)<!-- -->


This data visualization shows Sanne’s flight path off the coast of Senegal during the first week of January. Each day Sanne starts in what appears to be a protected natural area in the town of Fadiouth. She then takes flight over the Atlantic ocean, only to make a loop and return to an area by the coastal town of Palmarin. This happens each day, with trips occasionally being taken directly between Fadiouth and Palmarin. We can presume that she is going for her daily fish hunt. Since seagulls are omnivores and can also eat things that are found on land, on the days she does not fly out to sea she has probably located enough food on land. She might be bringing food back to a nest, but this does not align with her starting and ending destination being different.
There is only a slightly noticeable pattern in Sanne’s flight speed. While near land, she flies slowly, rarely exceeding 5 kilometers per hour. She flies the fastest when flying further into the ocean and on her return. Here she reaches speeds of 15 kph, with an average speed of 10 kph. Once far enough, she slows down to a speed of 0 to 5 kph again in order to look for prey more easily. Sometimes she’ll circle the area, but once she’s satisfied, she’ll  return. Her average flight speed is 2.450434 kpm.






![](SanneFlightMarch.gif)<!-- -->


The data visualization for March is less insightful. Sanne flies in a similar pattern to January. She starts from the city of St Louis and flies down a peninsula only to circle back and return to the city. There seems to be plenty of food in St Louis and the surrounding bay. The exception is a long trip up a river into Mauritania and back down the coast, and a journey into the ocean that ends abruptly. Sanne rarely picks up her speed except for when she takes detours from her normal path which require her to travel longer distances. While traveling in the urban area, she does not appear to go above 10 kpm.


## Conclusion 
![](threebirds.PNG)

**Why should *you* care about Nico, Eric, and Sanne?**

According to Planet Experts author, Daniela Ginta, seagulls are the ["Unlikely Canaries of Climate Change](http://www.planetexperts.com/seagulls-unlikely-canaries-climate-change/). Seagull populations are declining while human populations rise. As climate change causes Earth’s seas to warm, the ocean goes through acidification. Additionally, humans continue to overfish so gulls are facing a reduction in their sea-sourced food. This scarcity causes sea gulls to source more food from human garbage. Seagulls are not currently threatened by extinction, however, if such a hardy and widespread species is threatened by climate change – it is important to remember the countless species that cannot adapt as effectively. 
We must urgently acknowledge the consequences that climate change is having on every part of Earth’s ecosystems.
