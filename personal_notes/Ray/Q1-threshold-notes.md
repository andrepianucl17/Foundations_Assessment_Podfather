# Q1 reading notes: Lisbon’s 5% threshold and London’s 4%–7.5% range

## Lisbon’s 5% is a policy threshold / 里斯本的 5% 是政策门槛

Lisbon’s 2025 regulation divides the number of local accommodation establishments (*alojamento local*) by the number of permanent dwellings. Article 4(1)(b) sets the ratio for eligible parishes or neighbourhoods to be designated as **relative containment areas** at **5% or more and below 10%**. Article 6 limits new registrations in those areas to specified exceptions. The 5% refers to the whole area’s ratio.

里斯本 2025 年条例用当地短租住宿机构数除以常住住宅数。按第 4 条第 1 款 b 项，比例**达到 5% 但低于 10%**时，符合条件的堂区或街区可被划为**相对限制区**。按第 6 条，区内只有在条例列出的例外情况下才可获准新增登记。5% 指的是整个地区的比例。

- Município de Lisboa (2025), *Alteração ao Regulamento Municipal do Alojamento Local*, Aviso n.º 29926-A/2025/2, 5 December 2025. [Article 4, PDF p. 10](https://files.diariodarepublica.pt/2s/2025/12/235000001/0000200026.pdf#page=10) · [Article 6, PDF p. 11](https://files.diariodarepublica.pt/2s/2025/12/235000001/0000200026.pdf#page=11) · [Original PDF in this repository](sources/lisbon-rmal-2025.pdf)

## London’s 4%–7.5% is an observed range / 伦敦的 4%–7.5% 是观测范围

Using 2018 data, Shabrina, Arcaute and Batty found about **4–7.5 entire-home Airbnb listings advertised as available for more than 180 days per year per 100 dwellings** in some small statistical areas (LSOAs) in Camden, Westminster, the City of London and Hackney. The London-wide ratio under the same filter was about **0.25%**. The range compares different small areas. The availability measure refers to advertised availability.

Shabrina、Arcaute 和 Batty 用 2018 年数据发现，Camden、Westminster、City of London 和 Hackney 的部分小统计区（LSOA），每 100 套住宅对应约 **4–7.5 条全年可订超过 180 天的 Airbnb 整套挂牌**。用同样的筛选条件，全伦敦约为 **0.25%**。这个范围描述不同小区的挂牌集中度。180 天来自挂牌的可订信息。

- Shabrina, Z., Arcaute, E. and Batty, M. (2022), ‘Airbnb and its potential impact on the London housing market’, *Urban Studies*, 59(1), 197–221. [DOI and Figure 3(b)](https://doi.org/10.1177/0042098020970865) · [UCL Discovery PDF, p. 10](https://discovery.ucl.ac.uk/id/eprint/10120512/1/0042098020970865.pdf#page=10) · [Original PDF in this repository](sources/shabrina-arcaute-batty-2022.pdf). Unmodified publisher PDF, © Urban Studies Journal Limited 2021, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## How the sources relate to our Q1 / 这两份资料怎么用于 Q1

For discussion, we can use **5% as an external screening benchmark** for the number of entire-home Airbnb listings per 100 dwellings in each London borough. A borough at or above the line would be a candidate for closer investigation. Lisbon counts local accommodation establishments for regulatory purposes, and the London paper uses a restricted subset of listings at a smaller geographic scale. Our borough rates have their own numerator and denominator. These sources provide policy and historical context for the comparison.

组内讨论时，可以把 **5% 当作外部筛查线**，比较伦敦各区每 100 套住宅对应多少条整套 Airbnb 挂牌。达到筛查线的区可以优先调查。里斯本统计的是监管口径下的短租住宿机构，伦敦论文统计的是更小地理尺度下符合特定条件的挂牌。我们自己的行政区比例需要单独交代分子和分母。

## Conor’s cleaned listings / Conor 的清洗数据

[Conor’s cleaning notebook](../../data_prep/cleaning.ipynb) prepares a panel of eight snapshots. For the September 2026 snapshot, the notebook marks a listing as `active_ltm` when it has at least one review in the previous 12 months. A newly listed property with zero reviews therefore receives `False`, even if guests can book it. For Q1, compare the rate using all entire-home listings with the rate using entire-home listings with a recent review, and state the filter on the map. Borough rates should be recalculated using the chosen cleaned export and a dwelling-stock denominator.

[Conor 的清洗笔记本](../../data_prep/cleaning.ipynb)整理了八期快照。对 2026 年 9 月这期，过去 12 个月至少有一条评论的房源会被标记为 `active_ltm`。因此，刚上线、仍可预订但暂时没有评论的房源会被标为 `False`。Q1 可以分别比较「全部整套挂牌」和「过去 12 个月有评论的整套挂牌」两种口径，并在地图上标清筛选条件。各区比例应以选定的清洗输出和住宅存量重新计算。

The notebook contains both a single-snapshot export and a panel export, with different row counts in the saved outputs. Confirm which export to use before comparing borough rates. The previous borough figures are omitted here.

笔记本有单期和多期两种导出，保存的输出中，两者的记录数不同。计算各区比例前要先约定采用哪份清洗结果。这里不沿用此前的行政区比例。
