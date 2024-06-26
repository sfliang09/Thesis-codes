# Role of Medium-Duration Energy Storage: Compressed Air Energy Storage and Carnot Battery
Medium-duration energy storage model based on PyPSA-Eur and results analyses

## Abstract
Energy storage technologies are widely acknowledged as effective solutions during energy transition, such as Li-ion batteries and hydrogen which are able to mitigate the variability and intermittency in renewable energy generation. However, previous studies focused on assessment for short- or long-term energy storage systems, and the role of medium-duration energy storage (MDES) are not evaluated in a model in Europe. Here, we employ PyPSA-Eur with high spatio-temporal resolution, an expansion capacity model that co-optimizes the investment, dispatch and operation of generation, storage and transmission network. This model is used to explore the role of MDES technologies, namely compressed air energy storage (CAES), Carnot batteries (including pumped thermal energy storage (PTES), liquid air energy storage (LAES) as well as vanadium redox flow battery (VRFB), in the European electricity system alongside Li-ion battery and hydrogen as short-and long-term energy storage. The evaluation method combines system value analysis with market potential approach within feasible regions derived from technology future design space comprising combinations of energy capacity costs, power capacity costs and round-trip efficiencies. Energy capacity cost of MDES is the most influential factor, requiring a range of 5 to 50 €/kWh to reduce the total system cost> 1%. We find that CAES, serving as an MDES option, achieves a maximum benefit of 28 billion euros (~32%) with geographical constraints related to availability of natural storage caverns. Conversely, LAES, given current projected design parameters, offers
limited advantages as MDES. It may become cost-effective when energy capacity cost is lower than 50 €/kWh and round-trip efficiency exceeds 70%. PTES potentially plays an MDES role due to its relatively low energy capacity cost. In regions with high shares
of solar, the demand for MDES deployment is limited due to low round-trip efficiency (< 80%) of MDES technologies compared to batteries. However, VRFB, as an MDES option with a lower 50 €/kWh energy cost, has the potential to compete with batteries. On the other hand, regions dominated by onshore wind generation require more MDES deployment. Given circumstances of low energy capacity costs of ≤ 5€/kWh and high round-trip efficiencies > 60%, MDES could compete with hydrogen in meeting demand peaks. Additionally, MDES always operates on daily, weekly or synoptic patterns and serves as an intermediary between short- and long-term energy storage to realize a least-cost electricity system.

## This GitHub includes:
- PyPSA-Eur model and its required code and data adjustments to reproduce the results for thesis
- Jupyter notebook with plotting and analysis scripts




