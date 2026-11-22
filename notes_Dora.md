# Q1 reading notes — Dora

I’m looking at whether entire-home Airbnb listings are concentrated in a few London boroughs once we account for the number of homes in each borough.

## Reading

- Shabrina, Arcaute & Batty — [Airbnb and its potential impact on the London housing market](https://discovery.ucl.ac.uk/id/eprint/10120512/1/0042098020970865.pdf). I’m using this paper to think about what a London-wide average might hide and how to interpret areas with higher concentrations.

- Xu et al. — [The influence of neighbourhood environment on Airbnb](https://repository.uwl.ac.uk/id/eprint/7016/). This study looks at Inner London and gives us possible explanations for the pattern on our map, including proximity to attractions and transport.

## Housing data

- [UK government dwelling stock estimates, Table 125](https://www.gov.uk/government/statistical-data-sets/live-tables-on-dwelling-stock-including-vacants). I used the 31 March 2025 housing stock estimate for each borough to calculate entire-home listings per 1,000 homes.

## Snelling, Colebrook and Murphy (2016) — Airbnb concentration by borough

**Source.** Snelling, C., Colebrook, C. and Murphy, L. (2016) *Homesharing & London’s Housing Market*. London: Institute for Public Policy Research. See Figure 3.3, its figure note and the discussion immediately before it. [Read the report](https://ippr-org.files.svdcdn.com/production/Downloads/homesharing-and-london-housing-market-dec16.pdf#page=25).

### What the report found

In 2015, the number of entire homes offered on Airbnb was equivalent to less than 1% of London’s private housing stock. The borough figures varied widely, from almost 4% in the City of London to 0.01% in Sutton. This gives us a reason to look beyond the London average and ask how large the local housing stock is in each borough.

### Comparison with our June 2026 analysis

| Measure | IPPR study | Our analysis |
|---|---|---|
| Listings counted | Entire homes offered at least once during the 2015 study period | Distinct entire-home listing IDs in the 19 June 2026 snapshot |
| Housing denominator | Private housing stock | All dwellings on 31 March 2025, from government Table 125 |
| City of London | Almost 4 listings per 100 private dwellings | 500 listings across 7,770 dwellings, or 64.35 per 1,000 |

Both analyses identify the City of London as an area with a high concentration of entire-home listings. In our data it ranks second despite having only 500 listings. Westminster ranks first at 68.38 listings per 1,000 dwellings, 4.22 times the London-wide rate of 16.20. The different observation periods and housing denominators prevent us from using the two City of London figures to estimate growth since 2015.

### What our review filter adds to Q1

Of the 62,456 entire-home listings in our snapshot, 33,861 had received at least one review in the preceding 12 months. With this restriction, the City of London recorded 34.11 listings per 1,000 dwellings and still ranked second. The first four areas remained Westminster, City of London, Kensington and Chelsea, and Camden, in that order.

The report gives a practical reason to be cautious about housing loss: residents can let their own homes temporarily while they are away. Such a listing could also receive a guest review. Our results therefore show where listings are concentrated and how that pattern responds to the review filter. Estimating how many homes moved out of long-term renting would require evidence on their previous use.

[Analysis notebook](./q1_spatial_pressure.ipynb) · [Borough counts and housing denominators](./Borough_counts.csv)

## Quattrone et al. (2016) — What can a map of Airbnb supply tell us?

**Source.** Quattrone, G., Proserpio, D., Quercia, D., Capra, L. and Musolesi, M. (2016) ‘Who Benefits from the “Sharing” Economy of Airbnb?’, *Proceedings of the 25th International Conference on World Wide Web*. See Figure 1 and Sections 5.1, 5.2 and 6.2. [Read the paper](https://archives.iw3c2.org/www2016/WWW2016-Proceedings/proceedings/p1385.pdf).

### What the paper does

Figure 1 maps hotels, Airbnb houses and Airbnb rooms separately across London. The authors use 625 wards as their spatial units, distinguish Airbnb supply from demand, and investigate whether the distribution of listings is associated with distance from the city centre.

### Comparison with our Q1 analysis

| Question | Quattrone et al. | Our analysis |
|---|---|---|
| What does one area on the map represent? | A ward. This finer scale can show variation within a borough. | A borough-level area. Our rate summarises the area as a whole and can hide differences between its neighbourhoods. |
| What does the map measure? | Figure 1 shows counts by accommodation type. The Airbnb houses panel is the closest comparison with our entire-home sample. | We count entire-home listing IDs and divide by local dwelling stock to obtain listings per 1,000 dwellings. |
| How is demand treated? | The authors analyse supply and demand as separate measures. | We count listings. Requiring a recent review gives us a subset with evidence of guest activity; each qualifying listing still counts once. |

### What this changes in our interpretation

The City of London has 500 entire-home listings and 7,770 dwellings. Its rate of 64.35 listings per 1,000 dwellings ranks second among the 33 areas. This illustrates how a borough with relatively few listings can rank highly once we account for its housing stock. The borough average leaves open the question of where those listings cluster within its boundaries.

Of the 62,456 entire-home listings in our June 2026 snapshot, 33,861 received at least one review in the preceding 12 months. Under this filter, the same four areas lead in the same order. This supports our finding about the geography of supply. To assess who benefits financially, we would also need evidence on booking revenue, who receives it and where recipients live.

[Our analysis notebook](./q1_spatial_pressure.ipynb) · [Borough counts and housing denominators](./Borough_counts.csv)
