# calculations

| Variable | Symbol | Value | Unit | Source |
| :--- | :--- | :--- | :--- | :--- |
| Network Hashrate | HN | 296000 | GH/s | [https://etherscan.io/chart/hashrate](https://etherscan.io/chart/hashrate) |
| GPU Hashrate | HM | 31.2 | MH/s | [https://www.legitreviews.com/geforce-gtx-1070-ethereum-mining-small-tweaks-great-hashrate-low-power\_195451](https://www.legitreviews.com/geforce-gtx-1070-ethereum-mining-small-tweaks-great-hashrate-low-power_195451) |
| GPU Power | PM | 110.6 | W | [https://www.reddit.com/r/ethereum/comments/7vewys/10000\_tons\_co2\_per\_day\_and\_climbing\_eip\_858/dtrswyz/](https://www.reddit.com/r/ethereum/comments/7vewys/10000_tons_co2_per_day_and_climbing_eip_858/dtrswyz/) |

## Network Power Consumption \(PN\)

A baseline value for network power consumption can be found by multiplying the total network hashrate with a "best case" value for the power/hashrate ratio that a miner can achieve.

> PN = HN x PM / HM
>
> PN = 296000 \(GH/s\) x 110.6 \(W\) x 1000 \(MH/GH\) / \( 31.2 \(MH/s\) x 10^6 \(W/MW\) \)
>
> PN = 1049 MW

As a side note, people often confuse power \(W\) and energy \(power x time, eg. Wh\). For instance, assuming an average daily PNd of 1049 MW we can calculate that days Energy consumption by multiplying by the number of hours in a day.

> ENd = PNd x Td
>
> ENd = 1049 \(MW\) x 24 \(h/d\) / 1000 \(GW/MW\)
>
> ENd = 19.7 GWh

