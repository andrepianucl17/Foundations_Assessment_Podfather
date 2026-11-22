Sth that might be shared together.
## Q1 about "Host Concentration"

[Download the Excel results](./q1_host_concentration.xlsx)

## Additional Literature
## Essay1:
https://www.sciencedirect.com/science/article/pii/S0261517723000201?via%3Dihub. 

- The authors classify hosts by the number of properties they manage and re-estimate their results using different cutoffs. Our London analysis can apply the same logic to listing shares.

- Research method: The study combines **continuous-treatment difference-in-differences** with **two-stage least squares**. 

- Host classification and main findings: Hosts managing **one or two** properties fall into the private group, and those managing **three or more** fall into the commercial group. The authors chose 3+ because it falls within the range used in previous research. The difference between the groups persisted when the authors used **2+** and **4+** as alternative cutoffs. See Sections 5.1–5.4 and Table 8.

- For the group study:  **Q1 Host concentration.** Use **2+** to describe multi-listing hosts and **3+** to check sensitivity to the cutoff. In the group's current London entire-home results, the listing shares are **52.69%** at 2+ and **44.84%** at 3+. That comparison shows how the majority finding depends on the cutoff.

## Essay2:
https://research.edgehill.ac.uk/ws/portalfiles/portal/46408645/Home_or_hotel_A_contemporary_challenge_in_the_use_of_housing_stock.pdf

- Data and Research method: The author groups hosts by the number of listings they manage and reports each group's share of hosts and share of listings. **Table 3** uses all listings. **Table 4** first selects entire homes and apartments, then groups hosts by the number of entire-home listings they manage. 

- The 2+ definition and main findings: A single dwelling can be advertised both as an entire home and as a private room. Counting both adverts can therefore place a host with one dwelling in the 2+ group. Recalculating within the entire-home sample reduces this overlap. Simcock treats **two or more entire-home listings per host** as an indicator of potential commercial letting. In the entire-home sample, the share of listings managed by 2+ hosts rose from **about 35% in 2015** to **about 44% in 2019**. In 2019, **3,267** qualifying hosts made up about **12%** of the **28,100** hosts in the sample. They managed **19,630** of the **44,463** entire-home listings, or about **44%**.

- For the group study: - **Q1 Host concentration.** Use Table 4 as a historical reference for the same city. The group's 2026 entire-home 2+ listing share of **52.69%** is about **9 percentage points** above the published 2019 share. The snapshots come from September and April, respectively. Assessing a longer-term trend calls for additional same-season snapshots with consistent room-type and activity filters.

- **Q1 Borough distribution.** Westminster's **22.56%** in Table 7 is its share of all entire-home listings managed by 2+ hosts across London. To measure their share of supply within Westminster, divide the number of entire-home listings they manage in the borough by all entire-home listings in that borough. [Table 7][table7]

- **Q2 Defining professional hosts.** Use the entire-home **2+** threshold as one candidate measure of operating scale and compare it with **3+**. Simcock gives a reason to examine entire-home listings separately, and Milone et al. show how to test sensitivity to alternative cutoffs. [Milone et al. reading note](milone-et-al-2023.md)

- ### London Airbnb hosts with 2+ listings in 2019 and 2026

| Sample | 2019 host share | 2019 listing share | 2026 host share | 2026 listing share |
| --- | ---: | ---: | ---: | ---: |
| All listings | ≈18% | ≈47% | 20.22% | 55.45% |
| Entire-home listings | ≈12% | ≈44% | 15.15% | 52.69% |

A host qualifies as 2+ if they manage at least two listings within the relevant sample. Host share is the percentage of hosts who qualify. Listing share is the percentage of listings managed by those hosts.

The 2019 figures are rounded as reported in Tables 3 and 4 of Simcock (2023). The 2026 figures come from the group's September Inside Airbnb snapshot.

## Essay3:
https://link.springer.com/article/10.1007/s11609-024-00542-3

- Data and research method: The authors use **Inside Airbnb** snapshots to compare listing composition in **45 cities and tourism destinations from 2016 to 2023**. Their comparison over time starts with listings available for at least one day in the next 365 days. The spatial analysis uses listings with at least one review in the past year and a **500-metre hexagonal grid** to study hotspots in London, Amsterdam, Berlin and San Francisco in **December 2023**.

- Classification rules and the meaning of 60.4%:

1. The **2+ cutoff** identifies accounts with two or more listings. The authors call their listings professional multi-listings.

2. **120 days** distinguishes accounts with one listing. A listing available for fewer than 120 days is classified as amateur, and one available for at least 120 days is classified as professional single. Availability refers to the forthcoming year's calendar.

3. **50%** describes market composition. In Figure 1, the authors use a share above 50% to identify markets where professional multi-listings make up most of the supply. [Sections 3.2 and 4.1][paper]

Across the 45 locations, more markets came to have a majority of professional multi-listings over time. In the authors' **December 2023** London sample, hosts with 2+ listings managed **60.4%** of the **65,651 listings** included in the analysis. The numerator counts listings managed by these hosts, and the denominator is all included listings. 

- For the group study: - **Q1 — Host concentration.** In the December 2023 London sample, hosts with two or more listings managed 60.4% of listings. Use the share of listings managed by 2+ accounts to assess whether they supply a majority. A share above 50% indicates a majority of listings. Report their share of host accounts alongside it to show how many accounts manage that supply. The broader assessment also needs evidence on the local housing stock and the geographical distribution of listings.

- **Q2 — Estimating potentially professional host accounts.** In the study’s availability-filtered sample, classify accounts with two or more listings as professional multi-listing hosts. For an account with exactly one listing, classify it as professional single-listing if that listing is available for at least 120 of the next 365 days. Count distinct host_id values in each group and add the two counts to estimate the number of potentially professional host accounts under this rule.

## Essay4:
https://discovery.ucl.ac.uk/id/eprint/10120512/1/0042098020970865.pdf

- Data and methods:

**Spatial analysis.** The authors use **Inside Airbnb listings from 2015 to 2019** and **2015 Valuation Office Agency (VOA)** dwelling counts. They compare Greater London, boroughs and smaller census areas called Lower Layer Super Output Areas (LSOAs). Figure 3 shows both the borough and LSOA scales. [Data sources][data] · [Figure 3][map]

**Rent analysis.** The borough-level multiple regression relates the **2015 count of listings that pass the stricter screen** to changes in **Zoopla asking rents from 2015 to 2017**, controlling for tenure mix, net additional dwellings and distance to the centre. [Model specification][model] · [Table 2][regression]

- Screening criteria and findings:

1. **First screen.** Select **entire-home listings** offered for **more than 180 days** over a year. The authors assume **50% occupancy** to flag listings that could be booked for more than 90 days. Confirming actual bookings requires booking records. 

2. **Second screen.** Keep the listings from the first screen whose hosts have **two or more listings**. The authors call this *possible misuse*. Establishing whether a specific dwelling breached the rules would require booking and planning permission records.

3. **Spatial finding.** In 2018, about **8,200 listings** passed the first screen, equivalent to around **0.25%** of London's housing stock. About **5,300** passed the stricter screen, equivalent to roughly **0.16%** across London and **3.5%–7%** of local dwelling stock in some LSOAs.

4. Rent finding.** Boroughs with more listings passing the stricter screen in 2015 had larger estimated increases in asking rents between 2015 and 2017. The regression supports a discussion of the association. Estimating a causal effect or counting homes withdrawn from long-term rental would require further research design and property histories.

- For the group study: - **Q1 — Host concentration.** Finding we can cite.** A citywide share can obscure neighbourhood hotspots. Our 2+ and 3+ figures describe how listings are distributed across accounts. This study adds a geographic measure of how large that supply is relative to local housing stock.  **Assessment criterion.** Calculate **entire-home listings per 1,000 dwellings** in each borough. Repeat the calculation with a stricter numerator of **entire homes offered for more than 180 days and managed by hosts with 2+ listings**. Use the same borough dwelling count for both rates and report the dates of the listings and the dwelling counts. The rates help identify areas with greater potential exposure to short-term letting.
  
- **Q2 — Estimating potentially professional host accounts.** - **Finding we can use.** Among multi-listing accounts, we can identify hosts with at least one entire home offered for a substantial part of the year. This gives a way to see how the estimated count changes under a stricter screen. **Proposed group rule.** Count each account's listings by `host_id` in the London base sample. Select listings managed by **2+** hosts with `room_type` equal to `Entire home/apt` and `availability_365 > 180`. Count distinct `host_id` values among those listings for a stricter supplementary estimate. Kirchner and Pohl use **at least 120 days** to classify single-listing hosts. Shabrina et al. use **more than 180 days** to screen entire-home listings.

## My summary about Q1:

- Method:

 The main analysis uses entire-home and apartment listings from the September 2026 London Airbnb snapshot. We first select entire-home listings  and then count the listings managed by each host_id within that sample. 2+ identifies accounts that manage at least two entire-home listings.   This follows Simcock’s approach to analysing entire-home portfolios in London. We then raise the cutoff to 3+, keeping the same sample and      denominators, to test whether the majority finding depends on accounts with exactly two listings. The sensitivity check follows Milone et       al.’s approach of testing alternative listing-count cutoffs. We repeat both calculations in the full sample as a comparison. Simcock (2023),    Table 4 · Milone et al. (2023), Section 3.2.5 and Table 8

- Assessment criterion:

 Both shares use the same sample.

 - **Host account share** = qualifying accounts ÷ all accounts in the sample.
 - **Listing share** = listings managed by qualifying accounts ÷ all listings in the sample.

 A minority of accounts manages a majority of listings when its share of accounts is below 50% and its share of listings is above 50%. The       listing-share benchmark follows Kirchner and Pohl’s use of a majority threshold to describe the composition of supply. Kirchner and Pohl        (2024), Sections 3.2 and 4.1

- Results and interpretation:

In the entire-home sample, the 2+ group meets the criterion for a minority of accounts managing a majority of listings. Raising the cutoff to 3+ excludes accounts with exactly two entire-home listings from the qualifying group. These accounts manage 4,792 listings, so the group’s share falls by 7.85 percentage points, from 52.69% to 44.84%. A minority of accounts manages a substantial share at both cutoffs. The majority finding depends on including accounts with exactly two listings. The full sample shows the same change in majority status.

- What this means for Q1: Out of control

Host concentration is one indicator in assessing whether Airbnb is out of control in London. These results describe how listings are distributed across accounts. To assess potential pressure on the housing stock, calculate entire-home Airbnb listings per 1,000 dwellings in each borough. Shabrina et al.’s London study shows that a low citywide share can coexist with higher shares of local housing stock in some neighbourhoods. Estimating how many homes actually shifted from long-term rental to short-term letting requires property-level rental histories. Shabrina et al. (2022), Figure 3










