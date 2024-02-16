# Liquidity Pool

## How does a liquidity pool operate?

CrestSwap applies a 0.31% fee to all trades, where 0.20% is contributed to the liquidity pool of the traded token pair.

A liquidity pool (LP) consists of two tokens, such as ZETA and CPT tokens, enabling seamless exchange between the two.

Users can earn a portion of trading fees by depositing a token pair into the LP, known as "adding liquidity." In return, they receive an LP token representing their LP share.

These pools are formed by pairing different crypto tokens and depositing them into a smart contract. CrestSwap utilizes the constant product formula for its automated market (AMM) and liquidity pools, maintaining a balanced 50/50 split based on the assets' current values.

Liquidity pools, often termed "trading pairs," combine two tokens to generate a liquidity provider token. This setup enables swapping between the paired tokens.

For instance:

* Initially, 10 LP tokens represent 10 ZETA and 10 CPT tokens.
* 1 LP token equals 1 ZETA + 1 CPT.
* Following trades exchanging 10 ZETA for 10 CPT and vice versa, the ZETA/CPT pool now holds 10.015 ZETA and 10.015  CPT.
* Consequently, each LP token is valued at 1.00015 ZETA + 1.00015 CPT.

## POOL APR

Pool APR or Annual Percentage Rate, represents the yield generated from adding liquidity to a pool. By contributing to a pool, you receive 0.25% of all trades made on that pair relative to your pool share. These fees are continuously added to the pool, accumulating in real-time, and are available for claiming upon withdrawal of your liquidity.



{% hint style="info" %}
The trading fees you accumulate will be accrued in real-time and added to your existing position when you exit the Liquidity Pool.
{% endhint %}

Supplying liquidity carries inherent risks, including exposure to impermanent loss (IL).

In the event that the prices of the two tokens revert to their initial values at the time of liquidity provision, you will not experience any Impermanent Loss (IL).

Impermanent Loss (IL) is a risk associated with providing liquidity to a pool. It occurs when the price ratio of the token pair changes. The volatility of the assets in the pool influences the likelihood of experiencing impermanent loss. As the automated market maker (AMM) maintains a constant total liquidity, the ratio is adjusted to restore equilibrium.

The term "impermanent" accurately describes IL, as the token's value may return to its original price if left in the pool. However, if the investor withdraws their funds from the liquidity pool, the loss is realized.

Impermanent loss arises from bidirectional changes in the value of one or both tokens within a pair. The higher the volatility of the underlying tokens in the pool, the greater the likelihood of experiencing Impermanent Loss.

It's important to note that Impermanent Loss is not permanent and is only realized upon withdrawal from a Liquidity Pool.
