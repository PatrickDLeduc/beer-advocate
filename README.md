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
