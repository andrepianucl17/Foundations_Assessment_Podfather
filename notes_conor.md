@article{P01_Shabrina_Arcaute_Batty_2021,
  author       = {Shabrina, Zahratu and Arcaute, Elsa and Batty, Michael},
  title        = {Airbnb and its potential impact on the London housing market},
  journaltitle = {Urban Studies},
  year         = {2022},
  volume       = {59},
  number       = {1},
  pages        = {197--221},
  doi          = {10.1177/0042098020970865},
  url          = {https://doi.org/10.1177/0042098020970865},
  keywords     = {P01, Essential, London, spatial-analysis, housing, measurement}
}

### Note ###
- Looks at how AirBnB competes with the conventional housing market, what kinds of housing are involved and whether this activity from airbnb is associated with actual rental price changes.
- Airbnb could introduce more competition for residential properties.
- Looked at spatial distribution across spatial resolutions for sensitivity!
- We should also not fall to the spatial aggregation problem.
- Then went to Shannon entropy which measures the diversity of a distribution (here it means the different dwelling types in each Lower Layer Super Output Area (LSOA))
- Found that AirBNB misuse is negatively corr with the dwelling type entropy at -0.14
- Poses questions like:
  - Are Airbnb listings concentrated in homogenous areas, is there a relationship between airbnb concentration and private rental prevalnce, all can be used for q1.
- Went on into spatial modelling after and found an association where a 100% increase in airbnb misuse could be associated with an 8% increase in rental pricing.
- Important to note that none of this establishes any form of causality in the relationship.
- For us this can help in understanding to do sensitivity analysis when discussing what professional means in our context.

@article{P02_Kirchner_Pohl_2024,
  author       = {Kirchner, Stefan and Pohl, Simon C.},
  title        = {Selling out the city? {Airbnb}'s amateur and professional listings across cities, time, and hotspots},
  journaltitle = {Berliner Journal f{\"u}r Soziologie},
  year         = {2024},
  volume       = {34},
  pages        = {581--609},
  doi          = {10.1007/s11609-024-00542-3},
  url          = {https://doi.org/10.1007/s11609-024-00542-3},
  keywords     = {P02, Essential, professionalization, host-concentration, spatial-hotspots, London}
}

### Note ###
- Has airbnb transitioned from a sharing economy platform to a commercial marketplace is the questions that this paper aims to answer.
- This one helps with discussing who is a professional so defo read!
  - Use number of listings per host and availability of those listings over the year as measures.
  - An amateur is one listing available for <120 days.
  - Professional single is one listing for >120 days
  - Professional multi is more than one listing per single host.
- Useful that this notes that listing coords are randomized within 350m of the actual locations.
- They looked at historical time series analysis of pros vs amateurs in a lot of cities.
  - They find that pros are becoming more common across almost all cities.
- THey use Getis-Ord Gi* which identifies stat sig. clusters of airbnb listings. 
- Also used Kernel Density Estimation(KDE) due to the randomness of the coords as it helps show density better.
- They then take this and show the hotspots and who mostly operate there, pros or amateurs.
  - Found that pro multi listers dominate the marketplace.
  - Amsterdam, Copenhagen, Stockholm are all more amateur than other cities. 
  - Amateurs declined after COVID. 
    - In london specifically it has high density and hotspots with north of thames kind of where we live with lots of pros and brixton and hackney with lots of amateurs (makes sense ig).
- This study is really useful for the methods tbh!!!

@article{P03_Kim_Yeon_2025,
  author       = {Kim, Y. R. and Yeon, J.},
  title        = {Do short-term rental platforms affect housing markets? Evidence from {Airbnb} in {London}},
  journaltitle = {Tourism Management},
  year         = {2025},
  volume       = {111},
  pages        = {105204},
  doi          = {10.1016/j.tourman.2025.105204},
  url          = {https://doi.org/10.1016/j.tourman.2025.105204},
  keywords     = {P03, Essential, London, spatial-panel, spillovers, regulation, housing-prices}
}

### Note ###
- Airbnb and london house prices while accounting for spatial autocorr
- eval whether 90 day limit is working or nah.
- For 1. they use a Spatial Autoregressive dynamic panel model (SAR) (Ive used this before!)
  - This helps to differentiate between direct effects and indirect effects and also total effects (ie airbnb activity direct to house prices and then houseprices from neighbours effect and then the combined effects is total.)
  - In one bourough a policy can affect another yk.
- Found that housing prices are not independent across boroughs (shocker!) 
- Also found that Airbnb and average daily rate of the listings is positively associtated with housing prices. 
- Also found that total listing numbers have a nugative association with house prices aka density. They say that this may indicate oversupply. 
- Lastly, found that the 90-day limit may reduce housing prices but the non-parametric test was insig so yeah not so convincing. 
- We should take from this paper that spatial dependence is important especially if we look at pricing. And we can also look at their units of measurement on airbnb activity as it is different ones. They also do policy analysis so thats good.

@article{P04_Prentice_Pawlicz_2024,
  author       = {Prentice, Catherine and Pawlicz, Adam},
  title        = {Addressing data quality in {Airbnb} research},
  journaltitle = {International Journal of Contemporary Hospitality Management},
  year         = {2024},
  volume       = {36},
  number       = {3},
  pages        = {812--832},
  doi          = {10.1108/IJCHM-10-2022-1207},
  url          = {https://doi.org/10.1108/IJCHM-10-2022-1207},
  keywords     = {P04, Essential, data-quality, Inside-Airbnb, measurement, methodology}
}

### Note ###
- Focuses more on how reliable the data is that we are using to study airbnb.
  - It's crit so jon will like it. 
- THey look at inside airbnb and airdna and some other nobodies. Inside is nonprofit and airdna is comercial btw.
- Inside Airbnb is montly butttttt the scraping may miss listings and it is not a complete rep. Also the availability data should not be interpreted as actual bookings.
- AirDNA on the other hand is more frequent with daily, and has occupancy, revenue and pricing estimates but its not open source so we don't know how they do their methodology. Doesnt mean we cant use it but should be cautious ngl.
- One thing to take into account is that hotels and traditional accom also now advertise on Airbnb so that throws a wrench in our works. They cite a study that had to remove 12% of the listings cause they represented this traditional stuff.
- Also Inside Airbnb will only show the bookings made directly with the site and not third party sites so occupancy could be false. 
- Some studies also remove stuff with less than 3 reviews since it might have been fake or outdated or overpriced or testers. 
- Also note the same spatial inaccuracy that others did. Really imporant to take that into account. 
- We should take all of this into account when we write our brief!


@article{P05_GarciaLopez_et_al_2020,
  author       = {Garcia-L{\'o}pez, Miquel-{\'A}ngel and Jofre-Monseny, Jordi and Mart{\'i}nez-Mazza, Rodrigo and Seg{\'u}, Mariona},
  title        = {Do short-term rental platforms affect housing markets? Evidence from {Airbnb} in {Barcelona}},
  journaltitle = {Journal of Urban Economics},
  year         = {2020},
  volume       = {119},
  pages        = {103278},
  doi          = {10.1016/j.jue.2020.103278},
  url          = {https://doi.org/10.1016/j.jue.2020.103278},
  keywords     = {P05, Essential, causal-inference, housing-rents, house-prices, spatial-heterogeneity}
}

### Note ###
- This is important people!!!!!! 
- Actually tries to look at causal effects of airbnb activity on rents and property pricing in the big Barthelona.
  - They look at how landlords will switch from long term lets to short term lets (for those pesky tourists) due to increased profit for the landlords. 
    - This puts pressure on the housing supply.
- They also used Inside Airbnb but used more snapshots from 2015 to 2018 and then some tax authority for second hand appartment transactions and idealista for rent and sale prices. 
- The scale they look at is much finer than boroughs in London and would be equivalant to the LSOAs above.
- They use reviews to reconstruct bookings as Airbnb reports that 72% of guests leave a review. 
  - They also categorize pros as commercial activvity which is multihost listings and single
  -  host entire appratment with at least 5 reviews per quarter. 
- They used panel fixed effects models to measure causality (not gonna explain that mess, read the paper)
- They also use instrumental variables where they look at where airbnb listings are likely to appear and then when the activity expands. They use tourist attractions and google searches to do so. Still don't really understand it that well but we ball ig. 
- They also look at event study analysis where they analyze whether neighbourhoods that later became airbnb hotspots were already experiencieng faster market growth before the expansion. 
- They found some causality between the top decile of airbnb hunks and rent prices increasing. THey also found that airbnb is associated with fewer resident households in expanded into neighbourhoods. 
- Okay so what does this say for us? Well:
  - We need to be able to tell total listings from active listings, entire home and appartment listings, and comerical listings.
  - We should also conduct our analysis spatially (duh)
  - And lastly we should really never use causal language ever in our brief cause it is way to hard to prove. The methods here are cool but I think beyond us atp.


@article{P06_Barron_Kung_Proserpio_2021,
  author       = {Barron, Kyle and Kung, Edward and Proserpio, Davide},
  title        = {The Effect of Home-Sharing on House Prices and Rents: Evidence from {Airbnb}},
  journaltitle = {Marketing Science},
  year         = {2021},
  volume       = {40},
  number       = {1},
  pages        = {23--47},
  doi          = {10.1287/mksc.2020.1227},
  url          = {https://doi.org/10.1287/mksc.2020.1227},
  keywords     = {P06, Essential, causal-inference, housing-supply, rents, house-prices}
}

### Note ###
- They look at whether airbnb increases residential rent and housing pricing and if so how does that work. 
- This is from the US and has like a million Airbnb listings from 2008 - 2016. 
- They also used Zillow for house prices and rents. They scraped the listing data directly.
- They also use the instrumental variables strat since desirable neighbourhoods could attract both airbnb activity and investment and gentrification so yk rent goes up stonks go up type beat. 
- To combat this they used google searches once again as a proxy for awareness and attraction. They also used a measure of the pre-existing tourist attractiveness. 
  - They say that as airbnb becomes more widely known then the listings that were in tourist attractive places should have also gone up. 
- They found that for each 1% increase in listings in an area house prices and rent prices rose. at a median owner-occupancy zip they found that that airbnb growth is associated with 9 dollars in additonal rent and 1,800 dollars in house price growth per annum. 
  - Okay so how does it do so well the authors say that as a landlord moves a dwelling from long-term rental to short and the supply of homes for long term tenants falls then rents increase for the long term, same as barthelona. 
- They also suggest policy where taxes would be applied to landlords moving their properties from long term to short term lets. 

@article{P07_Bei_Celata_2023,
  author       = {Bei, Gianluca and Celata, Filippo},
  title        = {Challenges and effects of short-term rentals regulation: A counterfactual assessment of European cities},
  journaltitle = {Annals of Tourism Research},
  year         = {2023},
  volume       = {101},
  pages        = {103605},
  doi          = {10.1016/j.annals.2023.103605},
  url          = {https://doi.org/10.1016/j.annals.2023.103605},
  keywords     = {P07, Essential, regulation, Europe, professionalization, policy-evaluation}
}

### Note ###
- Looks at whether the regulation actualy changes the market and which of the regulatory instruments actually seem to work.
- They look at whether regulation reduces the number of entire appartment listings, does it change the balance between entire apartments and private rooms, does it reduce the number of hosts managing multi listings, and does it change where the Airbnb short term lets are (away from touristy areas)
- The instruments they look at are time limits on the number of days a property can be rented, zonal restrictions and quotas on specific areas, and whether agreements and obliccations for platforms to share data and block irrecular listings work.
- Looks at 16 euro cities with some having regulation and others not really. 
- Amsterdam is the most strict with regulation, then barcelona, london, paris and berlin. Shows what regulatory instruments other cities us and which london uses, most notably the time cap and authorization for extended use. 
- Authors try to show what would happen if the regulations hadn't been implemented. 
- They found that regulation compared to the counterfactual showed that entire apartment listings were reduced by 28.8% due to regulation, entire apartments relative to shared rooms were down 24.4% and hosts managing multi listings was down 25.2%. The spatial concentration was not sig. 
- Of the instruments that are used, the most effective was zonal restrictions, followed by platform cooperation and then time caps (ding ding good for us to talk about!).
- Shows regulation can have meaningful outcomes and esspecially for curbing commercial pros. 

@article{P08_Bosma_2022,
  author       = {Bosma, Jelke R.},
  title        = {Platformed professionalization: Labor, assets, and earning a livelihood through {Airbnb}},
  journaltitle = {Environment and Planning A: Economy and Space},
  year         = {2022},
  volume       = {54},
  number       = {4},
  pages        = {595--610},
  doi          = {10.1177/0308518X211063492},
  url          = {https://doi.org/10.1177/0308518X211063492},
  keywords     = {P08, Essential, professionalization, platform-urbanism, inequality, qualitative}
}

### Note ###
- This is great because it examines what professionalisation looks like. 
- Authors ask who is able to participate successfully in the economic oppurtuniteis that are created by airbnb and what conditions hinge on it. 
- They challenge home-shares who are the amatuers and profession host binary (critical perspective).
- They argue that commercial activity can occur on a small sacle and including room rentals.
  - Tells us to be critical of people as they could be a host that is managing for another entitiy. 
    - Thomas and Irena show how co-hosting can obsucre an unequal relationship between a person that actually performs the labour of the letting and then the person that has the finacial capacity to own the asset. 
  - Johannes also shows how he works for a company and was able to scale his letting buisness through data and software experties but not actual property ownership. 
  - They also argue that the platform iteself incentivizes short term lets to meat kpis on properties and the algo will push them. 
- Not sure how useful this one is but it was interesting ig.

@article{P09_Wachsmuth_Weisler_2018,
  author       = {Wachsmuth, David and Weisler, Alexander},
  title        = {{Airbnb} and the rent gap: Gentrification through the sharing economy},
  journaltitle = {Environment and Planning A: Economy and Space},
  year         = {2018},
  volume       = {50},
  number       = {6},
  pages        = {1147--1170},
  doi          = {10.1177/0308518X18778038},
  url          = {https://doi.org/10.1177/0308518X18778038},
  keywords     = {P09, Important, rent-gap, gentrification, urban-political-economy, spatial-analysis}
}

### Note ###
- Investigates the link between short term rentals and gentrification. 
  - Short term rent gap: platforms create a new potential revenue stream from existing housing which allows landlords to earn more from short-term visitors than from long-term tenants. 
  - Builds on the rent gap where if a property could make more than what it is currently generating then there is an incentive for reinvestment to capture higher return. 
    - This can be applied to short term rents which can be more profitable. 
  - The authors argue that turning a long term rental into a short term requires very little captial and thus makes it easy to change when the incentive is there. 
  - This is then possibly why lower income residents can be displaced and gentrification ensues.
  - There is also a geographic aspect to considr, tourist districts and residential neighbourhoods with good public transport connection, leidure and culture can capture more incentive to convert. 
  - It is thus important not just to consider where airbnb is now, but where it is likely to expand too (like above). 
  - Investigated NYC by looking at the share of residential rental income that went through airbnb and also the potential short term rental income that could be made relative to the long term rents. 
    - Found that entire home listings represented half of the active listings but actually generated three quarters of the platform revenue. Moreover, hosts that operated multiple listings generated 28% of the revenue (the authors note these are the commecial pros since thir activity could not be explained by only renting their primary residence.)
  - Found that Airbnb's share of the increase in residential rent payments was highest in manhattan when compared to nyc as a whole. 
  - Also found that Lower East Side, Harlem, Bedford-Stuy were prominet places where the potential for revenue was there if conversion where to take place. Willamsburg and midtown were less prominent. 
  - Also found a racial aspect where places where incentive was high was predominantly non-white. 
  - Need to go back to read the loss of long term housing cause I did not really understand it! 

@article{P10_Tornberg_2022,
  author       = {T{\"o}rnberg, Petter},
  title        = {How sharing is the ``sharing economy''? Evidence from 97 {Airbnb} markets},
  journaltitle = {PLOS ONE},
  year         = {2022},
  volume       = {17},
  number       = {4},
  pages        = {e0266998},
  doi          = {10.1371/journal.pone.0266998},
  url          = {https://doi.org/10.1371/journal.pone.0266998},
  keywords     = {P10, Important, revenue-inequality, host-concentration, platform-economy}
}

### Note ###
- Investigates whether airbnbs image of small-scale egalitaring home sharing actually matches its market structure. 
  - Used inside airbnb data from 97 cities and regions. 
  - Found that airbnb revenue is highligy concentrated with an average gini coef of 0.68 which means there is substantial inequality in the distribution of the host revenue. 
  - 10% of the hosts receive half of the market revenue.
  - London was found to be more unequal than the average. 0.73
  - Concentration was also found to be increasing over time rather than remaining stable. 
  - Laslty, gender and race played into the estimated revenue with black hosts receiving approxx 22% less revenue than white hosts on average. Women it was 12%.
  - In london this was even worse with black hosts at -39.2% and women at 16.9%. 

@article{P11_Hidalgo_Riccaboni_Velazquez_2024,
  author       = {Hidalgo, Alberto and Riccaboni, Massimo and Vel{\'a}zquez, Francisco J.},
  title        = {The effect of short-term rentals on local consumption amenities: Evidence from {Madrid}},
  journaltitle = {Journal of Regional Science},
  year         = {2024},
  volume       = {64},
  number       = {3},
  pages        = {621--648},
  doi          = {10.1111/jors.12685},
  url          = {https://doi.org/10.1111/jors.12685},
  keywords     = {P11, Important, economic-benefits, restaurants, employment, instrumental-variables}
}

### Note ###
- Looks at how short term rentals can generate increased tourist spending in residential neighbourhoods. 
- Possible way to spin it good or bad. 
- Makes the decision less simple though. 
- Airbnb means that tourist accom is more distributed across a wider geography than traditional hotels. Tourist that stay in short term lets will spend money near where they stay. Increases local demand then. 
- Looks at madrid between 2014 - 2019
- Read paper if you want to look at methods I didn't really get all of it.
- Found that airbnb stimulates local food and beverage businesses
  - When airbnb increases within in a census tract by 14 rooms this is associated with approximately one additional food and beverage establishment. 
  - It also shows tha commercial centers may change to meet this demand by converting to restaurants and other establishments. 
    - This also translates into approx 11 additional workers per 14 rooms on airbnb in a census tract. 
    - Restaurants were most likely to form, then bars, then cafes showing who benefits. 
    - These effects were also found to be stronger ourside tourist areas in residential neighbourhoods. 
- This shows that short term rentals can generate local economic benefits, the spatial distribution of the airbnb activity matters a lot, and that regulation should distinguish between different types of activity in different types of neighbourhoods. 

@article{P12_Farronato_Fradkin_2022,
  author       = {Farronato, Chiara and Fradkin, Andrey},
  title        = {The Welfare Effects of Peer Entry: The Case of {Airbnb} and the Accommodation Industry},
  journaltitle = {American Economic Review},
  year         = {2022},
  volume       = {112},
  number       = {6},
  pages        = {1782--1817},
  doi          = {10.1257/aer.20180260},
  url          = {https://doi.org/10.1257/aer.20180260},
  keywords     = {P12, Important, welfare, hotel-competition, consumer-benefits, economic-analysis}
}

### Note ###
- This one looks more at different regulatory scenarioes and how peer-peer accomodation affects travellers, hosts, and hotels. 
  - Airbnb can be good when local hotel capacity is constrained which can limit short term let prices. 
  - This one defines whetehr a host is an amateur or a professional by their supply flexibility, amateurs can use their homes for other purposes and choose whether they offer their rooms or not, pros are constrained to continous commercial use and lets are fixed. 
  - Looked at the 50 largest US cities.
  - Found that airbnb supply is approx three times more price-responsive and more elastic.
    - They create more capacity duirng periods of high demand. 
    - Without airbnb hotel revenues would be higher.
    - They also found that applying lodging-tax parity increases the gov revenue but reduces consumer surplys and host surplus.
    - With a simulated 90 day quota the consumer surplus is halved comapred to a complete ban. 

@article{P13_Medeiros_Gregory_2026,
  author       = {Medeiros, Marcos and Gregory, Amy M.},
  title        = {The Evolution of Short-Term Rentals Research in the {Airbnb} Era: A Systematic Literature Review},
  journaltitle = {Journal of Real Estate Literature},
  year         = {2026},
  doi          = {10.1080/09277544.2026.2655538},
  url          = {https://doi.org/10.1080/09277544.2026.2655538},
  keywords     = {P13, Important, systematic-review, research-map, housing, regulation}
}

### Note ###
- This is a lit review and really intersting.
  - Reccomend read but is more critical.
  - Uses prisma and thematic analysis.
  - They indentify a shift from research into the hospitality and guest experince and the competition with hotels toward housing affordability, property prices, professionalisation and regulation. 
  - Short term rent here is a form of finacialised real estate where properties make money like a hotel would. 
  - Shows that short term rent conversion can reduce effective long-term housing supply, increase rents and property prices (especially when in a already constrained market...)
  - The impacts can change geographically becasue it generates positive amenity effects from spending of tourists and local business activity and negatexternalites like gentrifation or noise and congenstion. 
  - Regulation can reduce this activity and housing market pressure but the effectiveness depends on the enforcement. 
    - for this data sharing is pivital as enforcement is easier.
    - taxation when bassed primarily self reporting is not great and can have limited effects. 
  - Regulation can also discourage residential investment which should be taken into account. 

@misc{P14_InsideAirbnb_Data,
  author       = {{Inside Airbnb}},
  title        = {Get the Data and Data Assumptions},
  year         = {2026},
  url          = {https://insideairbnb.com/get-the-data/},
  urldate      = {2026-11-10},
  keywords     = {P14, Essential-Methodology, dataset, data-documentation, Inside-Airbnb}
}

@misc{P15_London_90Day_Guidance,
  author       = {{Greater London Authority}},
  title        = {Short-term and holiday lets in London},
  year         = {2026},
  url          = {https://www.london.gov.uk/programmes-strategies/housing-and-land/buying-and-owning-home/guidance-short-term-and-holiday-lets-london},
  urldate      = {2026-11-10},
  keywords     = {P15, Policy, London, 90-day-rule, planning}
}

@misc{P16_GOVUK_SelfCatering,
  author       = {{HM Revenue and Customs} and {Department for Levelling Up, Housing and Communities}},
  title        = {Letting out a self-catering holiday home in England: rules and regulations},
  year         = {2026},
  url          = {https://www.gov.uk/guidance/letting-out-a-self-catering-holiday-home-in-england-rules-and-regulations},
  urldate      = {2026-11-10},
  keywords     = {P16, Policy, England, registration, business-rates, council-tax}
}

@misc{P17_ONS_ShortTermLets_2026,
  author       = {{Office for National Statistics}},
  title        = {Short-term lets through online collaborative economy platforms, UK: July 2023 to December 2025},
  year         = {2026},
  url          = {https://www.ons.gov.uk/peoplepopulationandcommunity/housing/bulletins/shorttermletsthroughonlinecollaborativeeconomyplatformsuk/july2023todecember2025},
  urldate      = {2026-11-10},
  keywords     = {P17, Policy-context, UK, tourism, official-statistics}
}


@article{P18_Ferreri_Sanyal_2018,
  author       = {Ferreri, Mara and Sanyal, Romola},
  title        = {Platform economies and urban planning: {Airbnb} and regulated deregulation in {London}},
  journaltitle = {Urban Studies},
  year         = {2018},
  volume       = {55},
  number       = {15},
  pages        = {3353--3368},
  doi          = {10.1177/0042098017751982},
  url          = {https://doi.org/10.1177/0042098017751982},
  keywords     = {P18, Important, London, urban-governance, platform-regulation, planning}
}

### Note ###
- still need to read!
