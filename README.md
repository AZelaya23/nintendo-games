# nintendo-games
nintendo games form 1990 to 2022
![image](https://user-images.githubusercontent.com/79028098/231306664-0a3a89ab-26fe-422c-8974-18b9ff5a6ecc.png)

In this project, I decided I wanted to work on something related to some of my interest. To think of a topic, I decided to take a dataset related to Nintendo video games since it was something I loved growing up. I came across a dataset that had some data related to Nintendo games and decided to work on it.

To start off, I went through and cleaned the game titles that had grammatical errors ins them such as "@s" or "Â" found within certain titles. Cleaning this made it easier to search by title down the line without needing to add those special characters.

Even the initial clean-up, I wanted to separate the genre cloumn into "genre" and "Sub Genre" since many titles have a main genre and a sub genre cateogrized by them. Examples such as "Super Mario Galaxy" is considered a platformer and an Action-Adventure game because of the general platofrming on Mario titles, but also the puzzle solving and "adventure" like characteristics.

In the dataset, we have the total units sold, so we can use this data to find the total profit from inital release to now. With some research, we can find the cost of a game depending on the platform and use that price * unit sold = total Profit. The number can consistantly grow even today, however, some will increase faster than others.

Another issue that I found during the analysis was the difficulty of catorizing each game into a respective Franchise. Although certain titles have a similarity to a series, creating a dashboard later would be difficult with having to find each title one by one and add it to the analysis due no franchise similarity. To solve this, I went on to use a function that pulled a franchise name from a table of content based on a keyword found in the game title. "Donkey" for "Donkey Kong", "Mario" for "super Mario" and "Zelda" for "The Legend of Zelda" are examples of catorizing the titles into their respective franchise.

AFter adjusting the dataset, I went on the create a pivot table so that I can create a chart based on the data from the pivot table. I created 3 different pivot tables with some similarities using Total Sales, Game title, Franchise, and Platform. With some tinkering, I developed a dashboard that consists of the sales from the Super Mario data collection.

Of course, the same process can be done with other Franchises such as "Pokemon", "The Legend of zelda", or "Final Fantasy".

As any dataset, this dataset can be adjust based on the current year, as some data will change as years pass.
