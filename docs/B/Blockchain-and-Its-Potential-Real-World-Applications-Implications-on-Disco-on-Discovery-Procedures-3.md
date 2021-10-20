---
layout: default
title: III. HOW BLOCKCHAIN WORKS
parent: § Blockchain and Its Potential Real-World Applications-Implications on Disco on Discovery Procedures   
grand_parent: B
nav_order: 30 
---
<style>
.dont-break-out {
  /* These are technically the same, but use both */
  overflow-wrap: break-word;
  word-wrap: break-word;

     -ms-word-break: break-all;
  /* This is the dangerous one in WebKit, as it breaks things wherever */
  word-break: break-all;
  /* Instead use this non-standard one: */
  word-break: break-word;
}

.youtube-container {
    position: relative;
    width: 100%;
    height: 0;
    padding-bottom: 56.25%;
}
.youtube-video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

</style>

<div class="dont-break-out" markdown="1">

1. TOC
{:toc}

## III. HOW BLOCKCHAIN WORKS
Blockchain transactions are also facilitated and verified by several decentralized computers on a Peer-to-Peer network. When a transaction occurs, the transaction is uploaded into a general blockchain transaction pool.<sup>45</sup> The node then pulls a group of transactions from the pool and compiles a number of these transactions into a block.<sup>46</sup> The data contained within the block is then converted into a cryptographic string of numbers and characters (known as a “hash”).<sup>47</sup> Once a block is created, the individual node tasks itself with solving a “cryptographic puzzle.”<sup>48</sup> The speed it takes to solve this puzzle is directly correlated with the amount of processing power that an individual node supplies to the server.<sup>49</sup> In order to incentivize node owners (known as “Miners”) to supply processing power and energy to the system, the blockchain algorithm rewards a random miner who has solved the cryptographic puzzle with “cryptocurrency,” either Bitcoin or whichever currency is tied to the specific blockchain the miner is mining for. <sup>50</sup> It is important to note that, for a large swath of blockchains, only a fixed amount of cryptocurrency can be mined.<sup>51</sup> After that fixed amount is

***
<sup>45</sup>. Greg Walker, Blocks: *Collections of bitcoin transactions*, LEARN ME A BITCOIN (Feb. 26, 2015), https://learnmeabitcoin.com/beginners/blocks.
{: .fs-2}
<sup>46</sup>. *Id*. 
{: .fs-2}
<sup>47</sup>. *Id*.
{: .fs-2}
<sup>48</sup>. *See* Shijie Zhang & Jong-Hyouk Lee, *Analysis of the Main Consensus Protocols of Blockchain,* 6 ICT EXPRESS 93, 94 (2020) (explaining the process known as a “Proof-of-Work” consensus protocol). Other methods of consensus exist, such as Proof-of-Stake or Practical Byzantine Fault Tolerance. 
{: .fs-2}
<sup>49</sup>. APPLIED CRYPTOGRAPHY AND NETWORK SECURITY CONFERENCE, PROCEEDING NOTES FROM THE 5TH INTERNATIONAL CONFERENCE 407 (Jonathan Katz & Moti Yung eds., 2007). 
{: .fs-2}
<sup>50</sup>. Melvin Draupnir, *What Is the Bitcoin Mining Block Reward?,* BITCOINMINING.COM (May 6, 2016), https://www.bitcoinmining.com/what-isthe-bitcoin-block-reward/ (explaining the process of selecting a random miner every ten minutes on the bitcoin blockchain); Alyssa Hertig, *Can Ethereum Scale?*, COINDESK (Dec. 3, 2020, 1:52 PM), https://www.coindesk.com/learn/ethereum-101/will-ethereum-scale (providing an example of another blockchain, Ethereum, which awards a miner every fifteen seconds). 
{: .fs-2}
<sup>51</sup>. The fixed amount depends on the algorithm of each blockchain. James K. Darlington III, *The Future of Bitcoin: Mapping the Global Adoption of World’s Largest Cryptocurrency Through Benefit Analysis* 9 (Apr. 21, 2014) (B.A. thesis, University of Tennessee, Knoxville) (on file with the author). The limited supply is intended to mimic currency which was previously tied to the price of precious metals to reduce the possibility for rampant deflation when the supply rises (which is where the term “mining” originates). Demelza Hays & Andrés Coronado, *Why Bitcoin Is Technically an Inflationary Currency— Even Though Its Purchasing Power Is Increasing*, FEE (Sept. 8, 2018),
{: .fs-2}
***

reached, miners will be rewarded with fees that are associated with each individual transaction.<sup>52</sup>

The transaction that the rewarded miner verified becomes a part of the next verified block on the chain, and the ledger is updated with that information.<sup>53</sup> That updated blockchain, which includes all previous transactions and the new transactions, becomes the accepted ledger and all following transactions will only be verified if they contain that most recent block.<sup>54</sup> This process removes the possibility of “double spending,” an issue which arises when multiple computers on the system have outdated ledgers.<sup>55</sup> Double spending allows a person to spend an amount multiple times before the transaction is verified by a number of nodes on the network.<sup>56</sup> Nodes on the network must reach consensus with other nodes on the network that they too have the most recently updated block and have seen that transaction occur.<sup>57</sup> The new block becomes the “standard” which all nodes must comply with.<sup>58</sup> If a node receives a transaction which does not include the most updated block, it must reject the transaction and restart the process.<sup>59</sup> This eliminates the risk of double spending.<sup>60</sup> All the computers on the network receive the new block and verify that its log is accurate to the new block it received.<sup>61</sup> In this way, the blockchain can then confirm the information it received and

***
https://fee.org/articles/why-bitcoin-is-technically-an-inflationary-currencyeven-though-its-purchasing-power-is-increasing/. 
{: .fs-2}
<sup>52</sup>. Melvin Draupnir, *How do Bitcoin Mining Fees Work?,* BITCOINMINING.COM (Apr. 29, 2016), https://www.bitcoinmining.com/bitcoinmining-fees/. 
{: .fs-2}
<sup>53</sup>. Draupnir, *supra* note 50. 
{: .fs-2}
<sup>54</sup>. Walker, *supra* note 45. 
{: .fs-2}
<sup>55</sup>. Usman W. Chohan, *The Double-Spending Problem and Cryptocurrencies* (University of New South Wales, Discussion Paper Series: Notes on the 21st Century, Discussion Paper, Jan. 6, 2021), https://ssrn.com/abstract=3090174. 
{: .fs-2}
<sup>56</sup>. *Id*. 
{: .fs-2}
<sup>57</sup>. Zhang, *supra* note 48.
{: .fs-2}
<sup>58</sup>. Ameer Rosic, *Blockchain Consensus: A Simple Explanation Anyone Can Understand,* BLOCKGEEKS, https://blockgeeks.com/guides/blockchainconsensus/ (last visited, Aug. 10, 2021). 
{: .fs-2}
<sup>59</sup>. *Id*. 
{: .fs-2}
<sup>60</sup>. Chohan, *supra* note 55. 
{: .fs-2}
<sup>61</sup>. Chris Hammerschmidt, *Consensus in Blockchain Systems. In Short.,* MEDIUM (Jan. 27, 2017), https://medium.com/@chrshmmmr/consensus-inblockchain-systems-in-short-691fc7d1fefe.
{: .fs-2}
***

ensure the reliability of the information by sharing consensus with the majority of the nodes.<sup>62</sup>

The consensus the blockchain requires ensures the reliability of the information in the blockchain.<sup>63</sup> In order for the information to be altered in any way, a hacker or bad actor would need to alter the information on the previously verified blocks, and then it must have enough computing power (51%) to override the consensus of all nodes that currently exist to ensure the altered transaction would have consensus and be verified.<sup>64</sup> In addition to the astronomical amount of processing power and capital required to control that amount of processing power, a hacker would require to alter the blockchain, hackers are disincentivized from hacking the system as the value of the cryptocurrency is correlated to the “immutable” characteristic of the blockchain.<sup>65</sup> If it were found in the general population that the blockchain could be or was compromised, the value of the currency would plummet, making the large capital investment in processing power essentially worthless by leaving the hacker with valueless currency.<sup>66</sup>

While hacking the blockchain requires an immense amount of processing power, it must be noted that smaller blockchains with less miners and nodes are more greatly susceptible to hacking.<sup>67</sup> In addition, tangential cryptocurrency marketplaces are still susceptible to hacking due to the fact that these tangential companies utilize traditional centralized servers.<sup>68</sup> The marketplace is currently working on solutions to create a

***
<sup>62</sup>. *Id*. 
{: .fs-2}
<sup>63</sup>. *Id*. 
{: .fs-2}
<sup>64</sup>. Congcong Ye et al., *Analysis of Security in Blockchain: Case Study in 51%-Attack Detecting,* 5 INT’L CONF. ON DEPENDABLE SYS. & THEIR APPLICATIONS (DSA) 15 (2018). 
{: .fs-2}
<sup>65</sup>. Venkata Marella et al., *Understanding the Creation of Trust in Cryptocurrencies: The Case of Bitcoin,* 30 ELEC. MKTS. 259 (2020). 
{: .fs-2}
<sup>66</sup>. Jiarun Hu et al., *The Fluctuations of Bitcoin Price during the Hacks,* 3 INT’L J. APPLIED RSCH. MGMT. & ECON. 10 (2020).
{: .fs-2}
<sup>67</sup>. *How Blockchain Can Be Hacked: The 51% Rule and More*, CIPHER, https://cipher.com/blog/how-blockchain-can-be-hacked-the-51-rule-and-more/ (last visited, Aug. 10, 2021). 
{: .fs-2}
<sup>68</sup>. Rohit Gupta, *Hacking Into Blockchain: Is Blockchain Security a Concern?,* PLUGANDPLAY (Apr. 30, 2019), https://www.plugandplaytechcenter.com/resources/hacking-blockchainblockchain-security-concern.
{: .fs-2}
***

more robust and secure cryptocurrency and blockchain space.<sup>69</sup>

In summation, blockchain can create a paradigm shift in the way transactions are facilitated between consumers. Instead of requiring a consumer to trust a bank with their information and funds, blockchain users can utilize blockchain as an alternative to the traditional banking service.<sup>70</sup> Because blockchain does not rely on the centralization of the ledgering process and instead spreads the ledger among all nodes within the system, users may feel their information and/or funds are more secure and less vulnerable to hacks or bad actors who have control of these ledgers.<sup>71</sup> This gives a user solace in the belief that they no longer must “trust” centralized banks, a fear which was spawned out of the mistrust of banks during the 2008 recession.<sup>72</sup> A completely digital currency based on blockchain has other desirable factors, such as fungibility, divisibility, portability, and durability.<sup>73</sup> Fiat currency has always drawn criticism,<sup>74</sup> but the motivation for Satoshi was cutting out the untrustworthy banking system middleman and putting the control back into the hands of consumers.<sup>75</sup>

***
<sup>69</sup>. Press Release, *The Future of Crypto-Commerce and Cybersecurity: AnChain.AI to Present at DEF CON 2019,* BUS. INSIDER (July 16, 2019, 12:00 PM), https://markets.businessinsider.com/news/stocks/the-future-of-cryptocommerce-and-cybersecurity-anchain-ai-to-present-at-def-con-2019- 1028357609.
{: .fs-2}
<sup>70</sup>. *How Blockchain Could Disrupt Banking,* CB INSIGHTS (Feb. 11, 2021), https://www.cbinsights.com/research/blockchain-disrupting-banking/.
{: .fs-2}
<sup>71</sup>. Marella, *supra* note 65.
{: .fs-2}
<sup>72</sup>. Nakamoto, *supra* note 17.
{: .fs-2}
<sup>73</sup>. John P. Kelleher, *Why Do Bitcoins Have Value?*, INVESTOPEDIA (June 30, 2020), https://www.investopedia.com/ask/answers/100314/why-do-bitcoinshave-value.asp.
{: .fs-2}
<sup>74</sup>. Detlev S. Schlichter, *The Case Against Fiat Money*, WALL ST. J. (updated Apr. 4, 2012, 12:01 AM), https://www.wsj.com/articles/SB10001424052702303816504577319610353583998.
{: .fs-2}
<sup>75</sup>. Nakamoto, *supra* note 17.
{: .fs-2}
***

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/B/Blockchain-and-Its-Potential-Real-World-Applications-Implications-on-Disco-on-Discovery-Procedures-1/">
I. THE BIRTH OF BITCOIN: BLOCKCHAIN ORIGINS</a></li><li> <a href="/docs/B/Blockchain-and-Its-Potential-Real-World-Applications-Implications-on-Disco-on-Discovery-Procedures-2/">
II. BLOCKCHAIN ILLUSTRATION</a></li><li> <a href="/docs/B/Blockchain-and-Its-Potential-Real-World-Applications-Implications-on-Disco-on-Discovery-Procedures-3/">
III. HOW BLOCKCHAIN WORKS</a></li><li> <a href="/docs/B/Blockchain-and-Its-Potential-Real-World-Applications-Implications-on-Disco-on-Discovery-Procedures-4/">
IV. PUBLIC, PRIVATE, AND PERMISSIONED BLOCKCHAINS</a></li><li> <a href="/docs/B/Blockchain-and-Its-Potential-Real-World-Applications-Implications-on-Disco-on-Discovery-Procedures-5/">
V. ALTERNATE USES FOR BLOCKCHAIN TECHNOLOGY </a></li><li> <a href="/docs/B/Blockchain-and-Its-Potential-Real-World-Applications-Implications-on-Disco-on-Discovery-Procedures-6/">
VI. DISCOVERY PROCEDURES FOR BANKING TRANSACTIONS</a></li><li> <a href="/docs/B/Blockchain-and-Its-Potential-Real-World-Applications-Implications-on-Disco-on-Discovery-Procedures-7/">
VII. JUDICIAL NOTICE</a></li><li> <a href="/docs/B/Blockchain-and-Its-Potential-Real-World-Applications-Implications-on-Disco-on-Discovery-Procedures-8/">
VIII. PUBLIC POLICY OF COST SAVING</a></li><li> <a href="/docs/B/Blockchain-and-Its-Potential-Real-World-Applications-Implications-on-Disco-on-Discovery-Procedures-9/">
IX. CONCLUSION</a></li></ul>
***

</div>
