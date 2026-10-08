# OKX perpetual futures: How perpetual contracts work, what they cost, and how to trade them with better risk control

When people search for **OKX perpetual futures**, they usually want more than a definition. They want to know which contracts are available, how leverage works, what funding fees really cost, whether OKX supports demo trading, and whether the platform is available in their country.

The short version: OKX perpetual futures are derivative contracts with no fixed expiry date. You can trade long or short, use isolated or cross margin, and settle contracts in currencies such as USDT or the underlying crypto asset. The trade-off is straightforward: leverage makes capital more efficient, but it also makes liquidation arrive faster when the market moves against you.

This guide explains the mechanics, fees, account modes, referral offer, and a practical workflow for using OKX perpetual futures without treating the leverage slider like a slot machine.

> **Important:** Perpetual futures are leveraged derivatives. They can produce rapid losses, including the loss of the margin supporting a position. Product access, leverage limits, fee schedules, and account features depend on your jurisdiction and account status.

## What are OKX perpetual futures?

A perpetual future is a contract that tracks the price of an underlying asset but does not have a scheduled expiry date. Unlike a traditional futures contract, you do not have to close the position because a monthly or quarterly settlement date has arrived. You can theoretically keep the position open as long as it continues to meet the platform’s margin requirements.

Because there is no expiry date forcing the contract price to converge at settlement, perpetual contracts use a **funding rate**. Funding payments are exchanged between long and short traders at scheduled intervals. When the funding rate is positive, long positions generally pay short positions. When it is negative, shorts generally pay longs. OKX states that it facilitates this exchange and does not retain the funding payment as a separate platform service fee.

OKX offers several ways to structure perpetual futures positions:

- **USDT-margined perpetual futures**, where the position is settled in USDT.
- **USDC-margined perpetual futures**, where supported.
- **Crypto-margined perpetual futures**, where the settlement asset can be the underlying cryptocurrency or another specified crypto asset.
- **Perpetual contracts linked to selected traditional assets**, such as commodities or stocks, where available in the relevant jurisdiction.

The exact list of contracts changes. OKX periodically adds, changes, or removes perpetual markets, and individual products may not be available in every region. A contract visible on one version of the OKX platform may not appear for another user.

## How does the funding fee work?

Funding is one of the most misunderstood parts of perpetual futures. It is not the same thing as the maker or taker trading fee.

The basic calculation is:

text
Funding fee = Position value × Funding rate


For a USDT-margined contract, position value is calculated from the number of contracts, contract size, multiplier, and mark price. For example, if a position has a notional value of 6,000 USDT and the funding rate is 0.1%, the funding amount would be 6 USDT for that settlement period.

OKX commonly displays an eight-hour funding schedule, with settlement times at 00:00, 08:00, and 16:00 UTC. However, the interval varies by contract. Some perpetual futures may settle every four, two, or one hour, and OKX can adjust the settlement frequency for certain crypto contracts when market conditions push the funding rate toward its cap or floor.

That creates three practical rules:

1. Check the current funding rate before opening a position.
2. Check which side pays at the next settlement.
3. Check the funding interval instead of assuming every contract follows the same schedule.

A position that looks inexpensive on the trading-fee screen can become expensive if it is held through repeated funding settlements. This matters most for swing trades and positions held overnight or for several days. Short-term traders also need to remember that paying funding is only one cost. Opening and closing fees, spread, and slippage still apply.

## OKX perpetual futures fees

OKX uses a maker-and-taker fee model. A taker order immediately matches existing liquidity, while a maker order adds liquidity to the order book and remains available for another trader to fill. A limit order is not automatically a maker order: if it executes immediately against existing orders, it can still be treated as taker volume.

For standard futures pairs, the published global schedule currently lists the following reference rates. Your actual rate can vary by jurisdiction, product group, account tier, and trading pair. The fee shown inside your own OKX trading panel is the one to use before placing an order.

| Fee tier | Asset or 30-day futures volume requirement | Maker fee | Taker fee | Access |
| --- | ---: | ---: | ---: | --- |
| Regular | Under $100,000 in assets or under $5 million 30-day futures volume | 0.0200% | 0.0500% | [ Open OKX perpetual futures](https://okx.com/join/CASH20) |
| VIP 1 | At least $100,000 assets or $5 million volume | 0.0160% | 0.0450% | [ Check OKX futures access](https://okx.com/join/CASH20) |
| VIP 2 | At least $200,000 assets or $10 million volume | 0.0150% | 0.0360% | [ View the OKX futures account](https://okx.com/join/CASH20) |
| VIP 3 | At least $2 million assets or $50 million volume | 0.0100% | 0.0280% | [ Trade perpetual contracts on OKX](https://okx.com/join/CASH20) |
| VIP 4 | At least $5 million assets or $200 million volume | 0.0080% | 0.0270% | [ Review OKX futures markets](https://okx.com/join/CASH20) |
| VIP 5 | At least $20 million assets or $600 million volume | 0.0050% | 0.0260% | [ See OKX VIP futures pricing](https://okx.com/join/CASH20) |
| VIP 6 | At least $50 million assets or $1 billion volume | 0.0000% | 0.0250% | [ Access OKX perpetual trading](https://okx.com/join/CASH20) |
| VIP 7 | At least $100 million assets or $1.5 billion volume | -0.0020% | 0.0200% | [ Open the OKX trading page](https://okx.com/join/CASH20) |
| VIP 8 | At least $250 million assets or $2 billion volume | -0.0050% | 0.0200% | [ Check available OKX fee tiers](https://okx.com/join/CASH20) |
| VIP 9 | At least $500 million assets or $20 billion volume | -0.0050% | 0.0150% | [ Explore OKX perpetual futures](https://okx.com/join/CASH20) |

The schedule above comes from an official OKX fee update for the relevant futures fee group, but OKX also warns that the latest applicable schedule depends on the user’s jurisdiction and instrument. The platform shows the rate currently applying to your account in the order placement panel.

For a simple example, a trader with the Regular tier opening a 10,000 USDT position using a taker order would pay approximately 5 USDT for that fill at a 0.05% taker rate. Closing the same notional value with another taker order would add another approximately 5 USDT, before funding and slippage.

The fee is calculated from the traded position value, not merely from the margin deposited. A 10,000 USDT position opened with 10x leverage still has roughly 10,000 USDT of notional value for fee purposes. This is why high leverage can make fees feel surprisingly large relative to the amount in the margin field.

Other possible costs include:

- Funding payments while a perpetual position remains open.
- Liquidation fees if the position is forcibly closed.
- Slippage during fast markets.
- Conversion or deposit costs, depending on how funds reach the account.
- Spread in products that are not traded through the standard order book.

The cleanest habit is to open the specific contract, check the fee panel, and estimate the cost using the intended position size before confirming the order.

## Isolated margin or cross margin?

OKX supports **isolated margin** and **cross margin** for perpetual futures.

With isolated margin, a specific amount of margin is assigned to one position. If that position is liquidated, the loss is generally limited to the margin allocated to it, subject to the platform’s rules and any applicable fees. Other available funds are not automatically used to support that isolated position.

With cross margin, eligible account funds are shared across positions. This can give a position more room before liquidation, but it also means a losing trade may draw on a wider pool of account equity. Under cross margin, a serious loss can affect more of the trading balance than the amount initially visible beside a single position.

A practical distinction:

- **Isolated margin** is usually easier to contain when testing a strategy or trading a volatile altcoin.
- **Cross margin** can be useful for portfolio-style hedging, but requires a clear understanding of shared collateral and correlated positions.

Neither mode removes risk. Isolated margin limits the margin assigned to the position; it does not limit price volatility, funding costs, or execution risk.

## Leverage and liquidation

Leverage controls how much position value can be opened relative to the margin. At 10x leverage, a trader may open a position with approximately one-tenth of the notional value as initial margin, subject to the contract’s requirements.

That does not mean a 10% adverse move is required for liquidation. Maintenance margin, fees, funding, position tiers, mark price, and other risk parameters affect the liquidation level. At very high leverage, a relatively small price movement can put the position below the required maintenance margin.

OKX uses the **mark price**, rather than simply the last traded price, when assessing liquidation conditions. The estimated liquidation price shown in the interface is an estimate, while the actual liquidation or position-reduction price depends on the mark price and the maintenance-margin rules applying at that time.

The platform may reduce a position in stages before fully liquidating it. If the position remains below the required maintenance level, the system can continue closing the position until the risk requirement is restored or the position is fully liquidated.

For risk control, the useful questions are not “What is the maximum leverage?” but:

- How much of the account can this position consume?
- What price invalidates the trade idea?
- Is the position size small enough to survive ordinary volatility?
- Is the funding rate reasonable for the expected holding period?
- Is isolated margin more appropriate than cross margin?
- Where is the stop-loss placed before the order is opened?

High leverage often looks attractive because the required initial margin is small. The same feature leaves less room for an adverse move. The order ticket may allow a large number; that number is not a recommendation.

## How to trade perpetual futures on OKX

The basic workflow is relatively direct.

### 1. Open or access an eligible OKX account

Use the provided referral link to check whether the account-opening offer is available in your region:

[👉 Use the OKX referral link for perpetual futures](https://okx.com/join/CASH20)

The supplied invitation code is **CASH20**. It is promoted with a claimed 20% rebate, but the exact benefit, eligibility rules, duration, and applicable products should be confirmed on the signup or rewards screen. Referral conditions can vary by jurisdiction and campaign status.

### 2. Complete verification and fund the account

After account setup, funds may first appear in a funding account. OKX’s trading workflow requires transferring the intended collateral into the trading account before opening a futures position. The transfer currency depends on the selected contract, such as USDT for a USDT-margined perpetual.

Do not transfer the full account balance simply because the futures interface makes it easy. Decide the maximum amount you are willing to use as trading collateral first.

### 3. Choose the contract and margin currency

Navigate to **Trade**, then select **Futures** or **Perpetual**. Choose the contract, such as BTCUSDT Perp, and confirm:

- Margin currency.
- Contract size.
- Current funding rate.
- Funding interval.
- Maximum leverage.
- Minimum order size.
- Mark price and index price.
- Available order types.

OKX’s own walkthrough uses BTCUSDT Perp as an example of a USDT-margined perpetual contract, where USDT is the settlement currency and BTC is the price unit.

### 4. Select isolated or cross margin

For a first live position, isolated margin is easier to reason about because the position has a defined margin allocation. Cross margin can be useful in more advanced hedging or portfolio structures, but it should not be selected casually.

### 5. Set leverage and position size

Set the leverage before placing the order, then calculate the position’s notional value. A useful position-sizing check is:

text
Position notional value = Margin × Leverage


This is only a rough planning formula. Actual margin requirements depend on the contract, tier, mark price, and account mode.

A lower leverage setting does not automatically make a trade safe. Position size relative to account equity matters more. A 2x position that is too large for the account can still create a serious drawdown.

### 6. Place the order with risk controls

Choose long if you expect the contract price to rise, or short if you expect it to fall. OKX supports limit and market-style order workflows, and its guide also describes attaching take-profit and stop-loss conditions before submitting the trade.

Market orders are useful when immediate execution matters, but they usually incur taker fees and may experience slippage. Limit orders can reduce execution cost when they rest on the order book, although an aggressively priced limit order may execute as taker volume.

### 7. Monitor funding and maintenance margin

Once open, monitor:

- Unrealized profit and loss.
- Mark price.
- Estimated liquidation price.
- Maintenance margin ratio.
- Funding countdown.
- Funding direction.
- Open orders that could increase exposure.

Funding is deducted from or credited to the position at settlement. A funding payment reduces or increases account equity, which can affect liquidation risk over time.

## Can beginners practice with OKX demo trading?

OKX provides futures demo trading on the web and app. Users can select a perpetual market, such as a USDT-margined BTCUSDT perpetual, and open simulated long or short positions with virtual funds.

Demo trading is useful for learning the interface, but it does not perfectly reproduce the emotional or financial pressure of live trading. A sensible practice sequence is:

1. Find the perpetual futures section.
2. Select demo trading.
3. Choose a contract and margin type.
4. Open a small simulated position.
5. Add a stop-loss and take-profit.
6. Watch funding, mark price, and liquidation estimates.
7. Close the position and review the order history.

The objective is to learn how the ticket behaves, how contract quantity maps to position value, and where important risk data appears. It is not to build confidence by taking oversized simulated trades. A demo account has an annoying habit of making every strategy look smarter than it is.

## Are OKX perpetual futures available in the United States?

This is a jurisdiction question, not a technical one.

OKX’s U.S. compliance disclosure says that certain services and products are not available to U.S. users, and that foreign OKX products are not intended for users located in the United States. The disclosure also distinguishes OKX US spot and related services from foreign OKX entities and products.

Some OKX pages hosted under U.S. regional paths discuss perpetual futures, but that does not mean every U.S. resident can access every perpetual product. Availability may depend on the user’s location, state, account entity, product type, and current terms.

Before depositing funds, confirm:

- Whether perpetual futures are available after identity verification.
- Which OKX entity would provide the service.
- Whether your state or country is restricted.
- Whether the specific contract is enabled for your account.
- Whether the advertised referral benefit applies to your region.

Do not attempt to bypass geographic restrictions with location masking or another person’s account. Product access is determined by the platform’s compliance rules and applicable law.

## Is OKX perpetual futures suitable for you?

OKX perpetual futures may be useful for traders who need to:

- Take long or short exposure without expiry dates.
- Hedge a spot crypto position.
- Trade crypto markets with a defined margin structure.
- Practice derivatives through a demo environment.
- Monitor funding, mark prices, and risk tiers in one interface.

They are less suitable if you are still unclear about the difference between margin and position value, cannot explain funding payments, or would need to use essential living money as collateral.

A reasonable starting framework is:

- Use demo mode before live trading.
- Start with isolated margin.
- Use modest leverage.
- Keep the position small relative to total account equity.
- Check the current funding rate and interval.
- Place the exit plan before entering.
- Review the fee panel for the exact contract.
- Confirm regional eligibility before depositing.

The most important number in a perpetual futures trade is not the maximum leverage shown by the platform. It is the amount you can lose while still being financially and psychologically able to follow your plan.

[👉 Check current OKX perpetual futures access and referral terms](https://okx.com/join/CASH20)
