# Canadian-Lottery-Playbook - Maximizing Expected Returns & Understanding Historical Lottery Demand
### Purpose: 
Analyze lottery demand and expected return for top three Canadian lotteries at different Jackpot values.

### Description:

🚨🚨🚨 Big flashing lights that shine $70 million. This scene repeats in supermarkets, convenience stores, and even pharmacies. Everyone has dreamed of winning the lottery, but how can we maximise our returns?

💰 This project aims to evaluate the expected value of lotteries at different Jackpot Values, and the number of tickets sold over time amongst the top 3 Canadian lotteries: LottoMax, Lotto 6/49, and the Daily Grand.

### Methodology:
1. Webscrape top three lotteries prize breakdown on different sites (code provided), code for webscraping LottoMAX referenced from chiqui-m https://gist.github.com/chiqui-m/1ec1a2e29a8052ce75306fd8b7a3ae9e
2. Construct dataframe for webscraped data
3. Create dataframe subset, grouping by year and calculating average lottery tickets sold, prize money for each Matching Number, total winners for each lottery at different Jackpot levels
5. Use win probabilities of different lotteries (from OLG) to calculate the expected value of each lottery at different Jackpot levels
6. Construct Visualizations and uncover insights

### Findings:
#### Lotto649 has the largest expected return at 120% at the 65million Gold Jackpot Value level
Surprisingly, LottoMAX Jackpot at 65 million only returns around 65% of the $5 ticket, and the return is worst at 5-15 million at ~30%. DailyGrand has an expected return of 51%. Ultimately, Lotto649 holds the largest expected return, largely due to the Gold Ball probability increasing at higher jackpot levels. The number of lottery tickets also increases from ~5 million to ~10 million which makes it more difficult to get the Gold Ball, but the odds will be higher on the players side.

![image](https://github.com/keithchhh/Canadian-Lottery-Economics/assets/145700071/3c1e2d2d-229c-4ebf-8805-4f7c725c918c)


#### Expected Values of different lotteries
The expected value is calculated at each jackpot value.

![image](https://github.com/keithchhh/Canadian-Lottery-Economics/assets/145700071/8479174e-8702-4122-b258-314cf3cad5a9)

#### Total Tickets Sold per Lottery
We can see that Lotto649 is gaining in popularity, which may be due to the introduction of the Gold Ball Jackpot. The players from LottoMAX may have shifted to Lotto649, while DailyGrand lottery tickets are largely sold the same amount from 2019 to 2023.

![image](https://github.com/keithchhh/Canadian-Lottery-Economics/assets/145700071/3d224bae-18cf-4408-a3da-cdd832478855)

#### Daily Grand assumption of 7 million jackpot as the largest amount when looking at present value and discount rate of 4%
Looking at the graph, we can see that even if an individual lives for 80 years, the present value is still less than accepting the 7 million jackpot alternative, therefore the individual should instead accept 7 million.

![image](https://github.com/keithchhh/Canadian-Lottery-Economics/assets/145700071/a0fe7727-ef04-48bc-8dc1-1c9dc2ea2aba)

#### Lotto649 Expected Value
Prize per Winner for different lottery amounts

![image](https://github.com/keithchhh/Canadian-Lottery-Economics/assets/145700071/9e1ee422-2858-4e5e-8d63-68965d52824d)

#### LottoMAX Expected Value
Prize per Winner for different lottery amounts

![image](https://github.com/keithchhh/Canadian-Lottery-Economics/assets/145700071/50b023e2-d844-4c68-8abf-dece2fae46b2)

#### DailyGrand Expected Value
Expected Value of Daily Grand: 1.5171532909193532

### Objectives of Study:

- Which lottery has the highest estimated return for individuals 💴 

- What the expected return is for each Jackpot value for Lotto649 / LottoMAX 💵

- Lottery Demand over Time 💷 
