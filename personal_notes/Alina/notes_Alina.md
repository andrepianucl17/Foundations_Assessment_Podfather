Sth that might be shared together.
## Q1 Host Concentration

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
- The **2+ cutoff** identifies accounts with two or more listings. The authors call their listings professional multi-listings.

- **120 days** distinguishes accounts with one listing. A listing available for fewer than 120 days is classified as amateur, and one available for at least 120 days is classified as professional single. Availability refers to the forthcoming year's calendar.

- **50%** describes market composition. In Figure 1, the authors use a share above 50% to identify markets where professional multi-listings make up most of the supply. [Sections 3.2 and 4.1][paper]

Across the 45 locations, more markets came to have a majority of professional multi-listings over time. In the authors' **December 2023** London sample, hosts with 2+ listings managed **60.4%** of the **65,651 listings** included in the analysis. The numerator counts listings managed by these hosts, and the denominator is all included listings. 

- For the group study: - **Q1 — Host concentration.** In the December 2023 London sample, hosts with two or more listings managed 60.4% of listings. Use the share of listings managed by 2+ accounts to assess whether they supply a majority. A share above 50% indicates a majority of listings. Report their share of host accounts alongside it to show how many accounts manage that supply. The broader assessment also needs evidence on the local housing stock and the geographical distribution of listings.

- **Q2 — Estimating potentially professional host accounts.** In the study’s availability-filtered sample, classify accounts with two or more listings as professional multi-listing hosts. For an account with exactly one listing, classify it as professional single-listing if that listing is available for at least 120 of the next 365 days. Count distinct host_id values in each group and add the two counts to estimate the number of potentially professional host accounts under this rule.








