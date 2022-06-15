# Beer Advocate
An analysis of BeerAdvocate.com's top 250 best beers.

Beer Advocate is one of the internet's most popular beer review and discussion sites, and has been around since 1996. Due to their popularity, they are also one of the most vibrant beer communities around. This project showcases my skills using web scraping and analyzes the most popular types of beers by style. I find that Stouts and IPAs are the most popular beer styles and dominate the top 250 beers (https://www.beeradvocate.com/beer/top-rated/).

![Stouts and IPAs dominate BeerAdvocates Top 250 beers](https://github.com/PatrickDLeduc/beer-advocate/blob/main/stout_ipa.png?raw=true)

Looking at the Canadian data, I find that the most popular beers are brewed in the most populated Canadian provinces: Quebec (34 beers), Ontario (32), and British Columbia (25). What's most surprising from this data is how low Alberta ranks on the list, with only 6 beers coming from that prairie province.

![Quebec and Ontario brewers have the biggest share on the top 100 Canadian beers list ](https://github.com/PatrickDLeduc/beer-advocate/blob/main/best_canadian_beers.png?raw=true)

Finally, looking at which breweries have the most presence on the top 100, I find that Bellwoods Brewery and Dieu Du Ciel are neck and neck at the top, with Driftwood brewery at a distant 3rd place. Collective Arts and Unibroue, my personal favourite craft beer brands, are tied for 4th place, with 5 beers each.

![Bellwoods Brewery and Dieu Du Ciel beers make up nearly one-quarter of the top 100 Canadian beers](https://github.com/PatrickDLeduc/beer-advocate/blob/main/best_canadian_breweries.png?raw=true)

## Top Canadian Breweries

My interest was piqued at this point, so I gathered data about all of the currently brewed beers from the 38 brewers who appear on the top 100 Canadian beers list. My first question was what styles of beer are most commonly brewed in Canada? According to this data, IPAs are by far the most frequently brewed beer style: 3.5 times as common as Stouts and Pale Ales.

![number_beers_by_style_(Canada)](https://user-images.githubusercontent.com/98104764/173133203-1caf16b7-b329-4121-b6a4-10fbf3f9c0a6.png)


This made me curious as to whether there was any distinction by province. Here I show the data from Ontario, Quebec, and British Columbia as they make up most of the breweries on the list. Alberta, New Brunswick and Manitoba have similar distributions. IPAs are clearly the most popular beer style in all three provinces with stouts and pale ales taking up 2nd and 3rd places in BC and Ontario . Quebec breaks the trend, with the largest number of farmhouse ales across all provinces. 

![beer_styles_by_province_sorted](https://user-images.githubusercontent.com/98104764/173133745-9df41e29-1c55-4f40-9a4d-2b5f82a8242e.png)

Looking into the sheer number of IPAs brewed in Canada, it turns out that many breweries have a base recipe for their IPAs and then mix in different fruits. Bellwoods Brewery from Toronto, Ontario alone has 105 different types of IPA, with 23 variations on their classic Milkshark IPA.


## International Statistics

After looking at the Canadian statistics, I decided to expand my analysis to look at the rest of the world. My initial question was who makes the strongest beer on average? Using the ABV (Alcohol by Volume: https://en.wikipedia.org/wiki/Alcohol_by_volume), I plotted the median ABV for each country. The dashed line represents the median ABV for all beers in the dataset. Keeping in mind that this is an American site and the data is biased towards the USA, the data suggests that Europeans still make the strongest beers on average. Apart from the USA, the top 10 countries are all European.

![median_beer_abv_by_country_02](https://user-images.githubusercontent.com/98104764/173888735-b18a0575-2e00-4808-a63b-2f36ceead41f.jpeg)

Although I'm not surprised that Denmark tops the list, I am surprised that Belgium was not in the top 3. Belgium is most famous for their abbey beers which all tend to be very high in alcohol content. It made me wonder just how the beers stack up in their average alcohol content by style. Looking at the figure below, the classic abbey styles (Quadrupel, Tripel, Dubbel) are all above the average ABV, only outmatched by barleywine and bière de brut. Barleywine and bière de brut are both styles of beer that take after wine: they are essentially wines brewed with grain instead of fruit. Barleywine is closer to beer in style and flavour, while bière de brut is brewed with similar techniques to making champagne.  

![median_abv_by_beer_style_expanded_02](https://user-images.githubusercontent.com/98104764/173889039-a30ba990-469e-44db-95f0-28cc89a47a72.jpeg)

