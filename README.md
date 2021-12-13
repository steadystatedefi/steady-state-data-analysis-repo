# DeFi Exploit Analysis

The official [Steady State Finance (SST)](https://steadystate.finance/) data analysis notebook is a collection of [multivariate statistical analysis](https://github.com/steadystatedefi) conducted by the Steady State Finance software development team. Throughout this analysis, we have answered questions exclusive to the decentralized finance(DeFi) industry's exploit patterns and proclivities based on data dating back to 2016. There is no agreed upon date for the inception of the DeFi industry, but what we now know as DeFi industry has been spearheaded by early DeFi lendning platform, Maker(2014) and a smart contracts plaform dubbed "the world computer" by developers Ethereum(2015). 

## Risk Analysis Database(RAD) v1 — beta (updated 08-23-2021) 

The Risk Analysis Database(RAD) hosts a dynamic collection of granular data in exploits/hacks in the decentralized finance industry. The granularity is represented in the exploit metadata we capture such as block ids, contract hashes, and hacker public addresses.

Within the RAD, the data values analyzed are the following: Date of Exploit, Market Cap, DVL(dollar value lost), and ETH gas used in exploit. The quantitative data guides risk assessment process as we determine the weight of risk using those factors coupled with qualitative and cateogorical factors.

## Market Cap Relevance
The following notebook has a parochial focus on the impact of the ($) dollar value of DeFi protocols' market cap and the nature of the exploit. In conclusion, we have gathered that protocols with low market caps during exploits tend to be orchestrated rug pulls.


#### 📉  Analyzing Protocols with Low Market Caps
Coalitions of token holders participate in ["pump and dump"](https://www.investopedia.com/terms/p/pumpanddump.asp) schemes meaning new token holders are invited to pump the price of the coin while old token holders immediately dump their tokens for profit. Protocols with high market caps have much more variance in exploit behavior. 

<!-- image -->
<p style="text-align:center;">
  <img src="LowCap.png" alt="Steady State Finance" width="400" class="center" style="border:none;"/>
</p>

#### 📈  Analyzing Protocols with High Market Caps
Protocols with high market caps tend to be subject to smart contract exploits and flash loan attacks. Smart contract exploits have resulted in over $500 million (USD) DVL in over 4 years in the DeFi industry. Market Cap at the time of exploits/hacks imperative relevance and will be assessed in the RAD risk assessment algorithm.
