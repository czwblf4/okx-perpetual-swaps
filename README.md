# perpetual swaps: How OKX Contracts Work, What They Cost, and How to Trade Them More Carefully

Searching for **perpetual swaps** usually means one of three things: you want to understand how these contracts work, you are comparing exchange fees, or you are looking for a practical way to trade crypto without dealing with expiry dates.

OKX uses the term **perpetual futures** for what many traders still call perpetual swaps. The contract structure is broadly the same: there is no fixed expiry date, traders can take long or short positions, and a funding mechanism helps keep the contract price near the underlying market price. The important details are the costs, margin rules, funding schedule, liquidation process, and whether the product is available in your jurisdiction.

This guide explains how OKX perpetual swaps work, how the fee tiers are structured, how funding affects a position, and what to check before placing a live order.

> Perpetual swaps are leveraged derivatives. A small price move can create a large gain or loss relative to your margin, and a position can be liquidated when its margin is no longer sufficient. Product availability, leverage, fees, and account rules can vary by jurisdiction and account status.

## What are perpetual swaps?

A perpetual swap is a derivative contract that tracks the price of an underlying asset without a traditional expiry date. Unlike a quarterly or monthly futures contract, you do not need to close or roll the position because a settlement date has arrived.

On OKX, the product is generally shown as **Perpetual Futures** in the trading interface. The platform previously used the term **Perpetual Swap Contracts**, then moved the product naming into the broader Futures section while keeping the same basic trading function.

A trader can usually:

- Open a long position if they expect the price to rise.
- Open a short position if they expect the price to fall.
- Use isolated or cross margin, subject to account mode and product rules.
- Adjust leverage within the limit allowed for that contract.
- Attach take-profit and stop-loss instructions.
- Hold a position beyond a normal futures expiry date because the contract has no fixed expiry.

The absence of an expiry date does not mean the position can be held indefinitely without cost. Funding payments, trading fees, margin requirements, price volatility, and liquidation rules still apply.

## How OKX perpetual futures work

A typical USDT-margined perpetual contract uses USDT as the settlement currency. For example, in a BTCUSDT perpetual contract, BTC is the underlying price reference and USDT is used for margin, profit and loss, and settlement.

OKX also supports crypto-margined contracts in some markets. Those contracts use the underlying cryptocurrency as the settlement currency. The contract page should be checked before trading because contract size, settlement currency, leverage limits, funding intervals, and risk parameters can differ between instruments.

The basic workflow is:

1. Fund the account.
2. Transfer funds into the appropriate trading account if required.
3. Select the perpetual contract.
4. Choose the margin mode.
5. Set leverage.
6. Select an order type and position size.
7. Review the estimated liquidation price, margin, fees, and funding information.
8. Open the long or short position.
9. Monitor margin ratio, unrealized profit or loss, funding countdown, and mark price.

OKX displays the current funding rate, the direction of the next payment, the funding interval, and the countdown in the trading interface. This matters because the funding rate can change while the position is open.

## Funding fees: the cost many beginners overlook

Funding is the mechanism used to keep a perpetual contract close to its underlying index price.

When the funding rate is positive, long positions generally pay short positions. When the funding rate is negative, short positions generally pay long positions. OKX states that it facilitates this exchange between traders rather than retaining the funding payment as a platform service fee.

The basic calculation is:

text
Funding fee = Position value × Funding rate


For example, if the position value is 10,000 USDT and the funding rate is 0.01%, the funding payment is:

text
10,000 × 0.0001 = 1 USDT


The payment direction depends on whether the rate is positive or negative and whether you hold a long or short position.

The default funding schedule is commonly every eight hours, but the actual interval is contract-specific. OKX notes that some contracts may settle every one, two, four, or eight hours. If market conditions become extreme and the funding rate reaches a contract’s cap or floor, the settlement frequency can be adjusted.

This creates two practical points:

- A trade that looks profitable before funding may be less profitable after several funding payments.
- Closing before the relevant assessment time may mean you do not pay or receive that interval’s funding, but the precise timing rules and assessment window matter.

Funding is not automatically “good” or “bad.” It is a carrying cost or potential income that depends on the direction and size of your position. Traders holding positions for minutes may care more about execution costs. Traders holding for days need to monitor funding much more closely.

## OKX perpetual swaps fee structure

OKX does not charge a monthly subscription fee simply for having an account. Perpetual trading costs generally include:

- Maker or taker trading fees.
- Funding payments or receipts.
- Potential liquidation-related fees.
- Deposit, withdrawal, conversion, or payment-provider charges where applicable.
- Any product-specific costs shown in the trading interface.

For futures and perpetual contracts, the trading fee is calculated from the executed notional value rather than only from the margin deposited. That distinction is important. Using 10x leverage does not make the trading fee apply only to one-tenth of the position’s notional value.

For a standard example listed by OKX, a 1 BTC position at a 20,000 USDT price has a 20,000 USDT notional value. At a 0.05% taker fee, the trading fee is 10 USDT. At a 0.02% maker fee, the fee is 4 USDT.

### OKX perpetual futures fee tiers

The following table reflects the fee schedule published by OKX for the listed futures pairs after the August 2026 fee update. The account asset threshold or 30-day futures trading volume can qualify an account for a tier. The applicable schedule depends on the user’s jurisdiction and the exact product group, so the fee shown in the order panel should be treated as the final check before trading.

| Tier | Asset threshold | 30-day futures volume | Maker fee | Taker fee | Access |
| --- | ---: | ---: | ---: | ---: | --- |
| Regular | Below $100,000 | Below $5 million | 0.0200% | 0.0500% | [ Open an OKX account and check perpetual futures access](https://okx.com/join/CASH20) |
| VIP 1 | At least $100,000 | At least $5 million | 0.0160% | 0.0450% | [ View OKX perpetual futures availability](https://okx.com/join/CASH20) |
| VIP 2 | At least $200,000 | At least $10 million | 0.0150% | 0.0360% | [ Check your available OKX fee tier](https://okx.com/join/CASH20) |
| VIP 3 | At least $2 million | At least $50 million | 0.0100% | 0.0280% | [ Explore OKX futures trading](https://okx.com/join/CASH20) |
| VIP 4 | At least $5 million | At least $200 million | 0.0080% | 0.0270% | [ Review OKX derivatives access](https://okx.com/join/CASH20) |
| VIP 5 | At least $20 million | At least $600 million | 0.0050% | 0.0260% | [ Check the current OKX futures conditions](https://okx.com/join/CASH20) |
| VIP 6 | At least $50 million | At least $1 billion | 0.0000% | 0.0250% | [ Open OKX perpetual futures](https://okx.com/join/CASH20) |
| VIP 7 | At least $100 million | At least $1.5 billion | -0.0020% | 0.0200% | [ Check OKX VIP eligibility](https://okx.com/join/CASH20) |
| VIP 8 | At least $250 million | At least $2 billion | -0.0050% | 0.0200% | [ View OKX futures trading options](https://okx.com/join/CASH20) |
| VIP 9 | At least $500 million | At least $20 billion | -0.0050% | 0.0150% | [ Review OKX perpetual trading access](https://okx.com/join/CASH20) |

A negative maker fee means the published schedule shows a maker rebate at that tier. It does not mean every order will receive a rebate, because the order must qualify as a maker execution and the account must meet the relevant requirements.

For most individual traders, the Regular tier is the practical starting point. The headline difference between 0.02% maker and 0.05% taker may look small, but repeated entry and exit can make it meaningful. A market order that opens and closes a 20,000 USDT position at 0.05% on both sides would generate approximately 20 USDT in trading fees before funding:

text
20,000 × 0.05% × 2 = 20 USDT


That calculation excludes slippage and assumes the entire order is filled at the same notional value. Real execution can differ.

## Maker and taker orders

A **maker order** adds liquidity to the order book. A limit order that sits on the book and is later matched may qualify as maker volume.

A **taker order** immediately matches existing liquidity. Market orders are normally taker orders, although order behavior depends on the exact order type and execution settings.

The lower maker rate is useful for traders who can wait for an entry or exit. The higher taker rate buys immediacy. During fast price movement, paying the taker fee may be reasonable because a limit order can miss the trade. During normal conditions, repeatedly using market orders can quietly increase the cost of a strategy.

The fee shown in the order preview is more useful than a generic fee table because it reflects the account’s current tier, product, order type, and jurisdiction.

## Isolated margin or cross margin?

OKX offers isolated and cross margin options for perpetual futures, subject to account mode and product availability.

### Isolated margin

With isolated margin, a specific amount of margin is assigned to the position. Other available funds are generally separated from that position’s margin.

The main benefit is easier risk containment. If the position is liquidated, the loss is tied more closely to the margin allocated to that position, although fees and other rules still apply.

Isolated margin is usually easier to reason about when testing a new strategy or trading a volatile asset. It does not make the trade safe, but it reduces the chance that one position automatically consumes the entire balance available to a shared margin pool.

### Cross margin

With cross margin, eligible account funds can be shared across positions. This may help support a position during temporary price movement, but it also increases the amount of account equity exposed to the position and its related losses.

OKX warns that, in cross-margin mode, a severe loss in one position can affect the broader balance associated with the relevant margin currency. The exact exposure depends on whether the account uses single-currency, multi-currency, or portfolio margin.

A common mistake is to view cross margin as “extra protection.” It can delay liquidation under some conditions, but it can also place more capital at risk. That is a tradeoff, not a free safety feature.

## Leverage and liquidation

Leverage lets a trader control a position larger than the margin deposited. It also makes the liquidation threshold closer to the entry price.

For example, a 10x position may require much less margin than a 2x position, but the account has less room to absorb an adverse move before maintenance-margin requirements become critical. The exact liquidation price depends on entry price, position size, leverage, margin mode, maintenance-margin tier, fees, funding, and other account conditions.

A position can be profitable based on price movement and still face increasing risk because of:

- Accumulated funding fees.
- A widening maintenance-margin requirement.
- A sudden mark-price move.
- Additional positions sharing the same cross margin.
- Slippage during a rapid market move.
- A reduction in account equity caused by fees.

OKX’s product documentation explains that funding deductions can reduce account equity and may contribute to position reduction or liquidation.

Liquidation can also involve a liquidation taker fee and a liquidation clearance fee. These are separate from ordinary entry and exit fees.

The sensible order of operations is to decide the maximum acceptable loss first, then choose position size and leverage. Starting with the maximum leverage shown in the interface and trying to make the stop-loss fit afterward reverses that process.

## How to trade perpetual swaps on OKX

The platform’s basic order flow is straightforward, but each setting affects the trade.

1. **Open the trading interface.**
   Go to the Futures or Perpetual section and select the contract you want to study.

2. **Check the settlement currency.**
   Confirm whether the contract is USDT-margined, USDC-margined, or crypto-margined.

3. **Review the contract information.**
   Check contract size, mark price, index price, funding interval, funding rate, leverage limit, and position tiers.

4. **Choose isolated or cross margin.**
   For a first live position, isolated margin is usually easier to monitor because the allocated margin is more clearly separated.

5. **Set leverage conservatively.**
   Leverage changes required margin and liquidation distance. It does not improve the underlying trade idea.

6. **Choose the order type.**
   A limit order may qualify for maker pricing if it adds liquidity. A market order generally prioritizes execution and may incur taker pricing.

7. **Add risk controls.**
   Consider setting take-profit and stop-loss conditions before submitting the order. Confirm whether the trigger uses last price, mark price, or index price.

8. **Review the order preview.**
   Check estimated margin, notional value, trading fee, liquidation estimate, and available balance.

9. **Monitor the position.**
   Watch the margin ratio, mark price, funding countdown, and unrealized profit or loss.

10. **Close deliberately.**
    Do not assume that closing a position removes every cost. Funding already assessed is not normally reversed, and the closing order can generate another maker or taker fee.

OKX also provides demo trading for futures through the web and app. The demo environment allows users to select a perpetual contract, open simulated long or short positions, and reset virtual assets after closing orders and positions.

That makes demo trading useful for learning the interface, testing order types, and seeing how position size changes the liquidation estimate. It does not reproduce every emotional or execution problem found in a fast live market, so a successful demo result should not be treated as evidence of a profitable strategy.

## Does the referral code give a 20% discount?

The supplied referral link includes the code **CASH20**. The stated “20%” refers to the referral arrangement’s commission, not necessarily a 20% trading-fee discount for the person using the link.

Do not assume the code reduces perpetual-swap fees by 20% unless OKX clearly shows that benefit in the signup or rewards terms for your region and account. The applicable fee tier is determined by the platform’s current rules, account status, trading volume, asset balance, product, and jurisdiction.

You can use the referral link to check the current signup flow and whether any user-facing promotion is displayed:

[👉 Check the OKX signup and perpetual futures offer](https://okx.com/join/CASH20)

Promotions can have eligibility requirements, regional restrictions, expiration dates, minimum deposits, trading-volume conditions, or separate reward claims. If the terms are not displayed in the account interface, do not count a potential reward as part of the expected trading return.

## What to check before choosing an OKX perpetual swap

Before opening a position, confirm the following:

- Is the contract available in your jurisdiction?
- Is the product crypto-margined, USDT-margined, or another margin type?
- What is the current maker and taker rate for your account?
- What is the funding rate and how long until the next assessment?
- Is funding settled every one, two, four, or eight hours?
- What is the contract’s maximum leverage?
- What are the position and maintenance-margin tiers?
- Does the order use isolated or cross margin?
- Which price type triggers the stop-loss?
- What happens if the contract is delisted?
- Are there separate liquidation or clearance fees?
- How much of the account balance can realistically be lost?

Contract listings and availability can change. OKX has published both new perpetual listings and delisting notices, and its documentation repeatedly states that not every product is available in every region.

## Is OKX suitable for perpetual swaps?

OKX offers the core features perpetual traders usually look for: long and short positions, multiple margin modes, contract-specific funding data, limit and market orders, take-profit and stop-loss tools, demo trading, and a tiered futures fee schedule.

The more important question is whether the exchange and product fit your actual use case. A high-volume trader may focus on maker and taker fees, API execution, liquidity, and VIP thresholds. A newer trader may care more about demo access, clear margin controls, and the ability to use isolated positions. Someone holding for several days should focus on funding and liquidation distance rather than looking only at the entry fee.

For many users, the most defensible starting point is to use the demo environment, study one liquid contract, keep leverage modest, and compare the live order preview with the published fee schedule before committing capital. Perpetual swaps can be useful for hedging or directional exposure, but the lack of an expiry date does not remove the costs and risks of leveraged trading.
