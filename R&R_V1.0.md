# Lowering Greehouse Gas Emmissions in Industrial Operations Using Machine Learning


## Introduction

The decsion to write a piece on such a vague title as this is an admittedly self interested one. I want to know what the intesection of industrial climate action and datascience is so that I might be better equipped to be involved, if you are reading this perhaps you do too. 

I work as a process engineer and for many of the projects I have and will continue to work on the name of the game is efficency. How can we make money, whilst saving money and if the stars align how can we do that while leaving less of a mark on the planet. As of recently I possess some very, very rudimentry skills in datascience. While I may not be able to wield these to any great effect yet it is my hope that one day, if I use use them correctly, I can make a positve impact on reducing GHG emmissions. Nobel, I know. So, if that is to be the case best do some research on how ML has been applied in the wild.

Before we get into it though. In most of the research I came across the same concern was commonly raised when speaking of efficiencies in production reducing GHG emmissions and that is the Jevons Paradox. Whereby, greater efficiency may actually increase production of GHGs. It is worth noting that incentives to reduce GHG emmissions need to go beyond operational efficiency and saving money on operting costs for these to be viable. 

So here we go...


### Interesting application number 1:

There is an interesting application that was written about by google engineer, Thomas Olavson and his team. The idea they were putting across was to consider scheduling load intensive practices that are time flexible to periods of power generation in your network where there is low carbon instensity. 
Taking a step back, depending on where you live in the world the power you consume will be made up of a variety of sources, coal, wind, solar gas ect. What carbon intensity means in reference to power generation is how much carbon dioxide is generated as a result of generating power. For example the median value for coal without scrubbing is 1001g CO2/kWh, whereas the median value for hydroelectric is 4g CO2/kWh. As you might imagine the carbon instensity for power generation on a grid is not constant either. During certain periods, depending on environmental conditions or fuel prices the carbon instensity may shift. When the sun is shining or the wind is blowing low intensity sources may be plentiful but during lulls that capacity needs to be supplimented by higher intensity and storable fuels like coal or natural gas. To put it in perspective, in the case of Thomas' application they found that "the dirtiest hour of the day is 46% more carbon intensive than the cleanest hour of the day, when averaging over all days of the year and all our datacenter sites".
That shift presents an opportunity, using machine learning Thomas Olavson and others have shown that you can reliably forecast the carbon intensity of a grid.
Using this information allows businesses to take this into account when scheduling load intensive operations. In the case of Google datacentres this allows them to dynamically redirect server traffic to centres with spare capacity in low intensity grids.

This is not a necessarilly new practice, this method has been previously applied for operations cost reduction to optimze load for peiods where the energy cost is lower, but it is taking that practice and viewing it through a different lens. In addition this does not require a tremendous capital investment either and there exist several APIs where the intensity data can be pulled from today, either for industrial application or for consumer use at home.
Google's application may seem complex but it takes little imagination to think what operations are or can be flexible and scehdule them for time of the day where the environmental burden would be lessened. See:

https://carbonintensity.org.uk/#:~:text=The%20carbon%20intensity%20of%20electricity,carbon%20intensity%20from%20metered%20generation.


### Interesting application number 2:

Reducing Overproduction:
The over production of products represents a particullay acute problem in todays society. Global excess inventory was $8 trillion worth of goods in 2011 according the counil of supply chain management professionals. This is in part due to mis-calculations on demand forecasting which can be potentially better estimated with ML. Better forecasts allow for the application of just in time manufacturing, reduces overproduction and reduces the need to hold inventory in climate controlled warehouses. It's a win on all fronts frankly. This is particularly true of perishables or retail goods that can quickly fall out of fashion (think H&M or Shein). JIT manufacturiing is not a silver bullet though, it can have higher emmissions depending on the local characteristics of the supply chain. e.g. more short trips versus fewer trips with a larger capacity and is largely product dependent (e.g. the time it takes to grow an avocado is "fixed"). 
Sticking with over production, when it comes to food 1/3 of all food produced goes to waste (1.3 billion metric tons). The following is wild and is copied vertbatim, "in developing countries 40% of food waste occurs between the harvest and processing and retail. Whereas in industrialized nations 40% of food is wasted at the end of the supply chain, that is in ours stores, restaurants and home kitchens". 

Freight Routing and consolidation:
considering the clustering of suppliers based on their geographical location. Receive consolidated shipments to reduce half empty transported, lower the number of trips ect. Freight auctions is an interesting concept. Sell remaining capacity on your transporter



The options are endless and this article is not completed. References to be added.


Measuring GHG emmisions and sharing best practices.
This is a side note in what I've read but it is an interesting problem. We need companies to share best practice knowledge on how they assess and reduce GHG emmisions in their supply chain and manufacturing so that these can be consolidated. ML can be hypothetically applied to show what is the cleanest option given your product and circumstances.


Credit where credit is due here are my references:
    - https://towardsdatascience.com/how-data-scientists-can-reduce-co2-6b3249e0eb61 
