# AirBnB in New York City

### By Julie Olin, Julian Skovhus & Mik Lokdam

AirBnB is an online platform that accommodate guests with short-term lodging options that is mainly provided by private hosts. AirBnB is mainly used by travellers when looking for homestay rentals for a vacation and was founded by Brian Chesky in August 2008. Since the incorporation, the company has experienced an exponential growth and now accounts for upwards of 20% of the vacation rental industry as a whole.

In this article, we will explore AirBnB data for New York City in 2019. We'll take a deeper 
In New York City (NYC), more than 48.000 listings were available for rent in 2019. Listings range from a whole penthouse apartment with panorama view overlooking Central Park to a shared bedroom in Brooklyn and with the vast variety in accommodation options, NYC is set to fullfill the need of any traveller. As a tourist, it may be overwhelming to choose a place to stay in NYC as NYC is a very diverse city with 5 boroughs. Also, each borough contains serveral districts, each with their own charm and caracteristics. Should travellers choose to stay in the posh Manhattan, the hip Bronx or the cultural Brooklyn? And which characteristics defines each of these borough?

We help answer this. Let us start out with some basic stats to outline some differences between the 5 boroughs. The listings are distributed as follow:

<style type="text/css">
.tg  {border:none;border-collapse:collapse;border-color:#ccc;border-spacing:0;}
.tg td{background-color:#fff;border-color:#ccc;border-style:solid;border-width:0px;color:#333;
  font-family:Inconsolata , sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{background-color:#f0f0f0;border-color:#ccc;border-style:solid;border-width:0px;color:#333;
  font-family:Inconsolata , sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-fymr{border-color:inherit;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-fymr">Borough</th>
    <th class="tg-fymr">Residents</th>
    <th class="tg-fymr">AirBnB listings</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-fymr">Manhattan</td>
    <td class="tg-0pky">1.593.200 (19%)</td>
    <td class="tg-0pky">21.661 (44,3%)</td>
  </tr>
  <tr>
    <td class="tg-fymr">Brooklyn</td>
    <td class="tg-0pky">2.511.408 (31%)</td>
    <td class="tg-0pky">20.104 (41,1%)</td>
  </tr>
  <tr>
    <td class="tg-fymr">Queens</td>
    <td class="tg-0pky">2.256.576 (28%)</td>
    <td class="tg-0pky">5.666 (11,6%)</td>
  </tr>
  <tr>
    <td class="tg-fymr">Bronx</td>
    <td class="tg-0pky">1.364.566 (17%)</td>
    <td class="tg-0pky">1091 (2,2%)</td>
  </tr>
  <tr>
    <td class="tg-fymr">Statens Island</td>
    <td class="tg-0pky">475.014 (6%)</td>
    <td class="tg-0pky">373 (0,8%)</td>
  </tr>
</tbody>
</table>

One thing to notice is Manhattan and Brooklyn. Although Manhattan and Brooklyn make up 50% of the total population in NYC, they make up more than 85% of the total AirBnB listings. This indicate that these boroughs are attractive to tourists. Not surprisingly, because who wouldn't stay near the iconic Brooklyn Bridge or Times Square, dubbed 'the center of the world'?

A violin plot is a great tool to visualize summary statistics, so let's compare some prices between the 5 boroughs.

![violinplots_boroughs](images/fig1.png)

With out going into too many details of the violin plot, the white dot represents the median and the wider sections of the violin plot represent a higher probability that AirBnB listings of the borough will take on the given value.
Looking at price differences visualised in a violin plot, it is clear that Manhattan is also the most expensive borough a median price of 130$ pr. night, while Brooklyn have a median of approx. 90$ follows approx. the same price pattern as the other boroughs. 

The majority of tourists associate with NYC with Manhattan, making the two almost synonymous. Manhattan also houses the most tourist attractions in NYC - Times Square, Central Park, Empire State Building, Wall Street, Statue of Liberty just to mention a few. Since Manhattan has the most AirBnB listings and a myriad of tourist attraction, it's a hotspot for tourism. 

Let's take a deeper look into Manhattan.

Manhattan also houses many neighbourhoods. Ranging from Battery Park City in the very South to Marble Hill in the North, each neighbourhood has different characteristics regarding the price and availability of AirBnBs. 

The map below show the average rent price for AirBnBs in a given neighbourhood and by moving the mouse cursor over one the neighbourhood, more information such as the name of the neighbourhood and number of AirBnBs per square kilometre. If you wonder why there is a big uncoloured square in the middle, this is the iconic Central Park. Huge park, very great park, you should try it! 

<iframe src="mymap.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

Note that some of the smaller neighbourhoods have been merged together. From the map we see that neighbourhoods in the upper Manhattan has lower average rent prices for AirBnBs, whereas neighbourhoods in the lower Manhattan and around the Central park has the most expensive rentals. But why though? 
Looking at the neighborhoods that makes up the nothern part of Manhatten, the neighbourhood Harlem dominates. Harlem is formerly known as a ghetto and was back then a very poor and trobuled area with high crime rates. Today, Harlem has bloomed and the neighbourhood is today a very hip place with great vibes. But of course the area is still behind on some parameters compared to other neighbourhoods due to the history. 

On the other side of the spectrum in the lower Manhattan, Tribeca is to find. The histogram below show how Tribeca is significantly most expensive neighbourhood to rent an AirBnB in. 

![price_ranges](images/fig4.png)

Tribeca became an exclusive living area due to a substitution of industrial companies with artistic civilians during the 1960-70s. Today, Tribeca is known for it's many celebrities who recides in the neighbourhood and enjoy luxury living in relatively quieter sorroundings.

Prices pr. night is of course related to the type of rental. It is possible to rent either a full apartment, a private room or a shared room depending on your needs. Below, an interactive graph of the average prices on room types for each neighboirhood.

[plot](/bokeh_plot.html)

Now we have had a small introduction to Manhattan. So which AirBnB to choose? Below, all AirBnB locations is plotted to the map. By using the zoom-function, the map is able to provide the exact location, price pr. night and a small description of the AirBnB place. Try it and may you explore some hidden gems of AirBnB rentals!

<iframe src="mapcluster_final1.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

