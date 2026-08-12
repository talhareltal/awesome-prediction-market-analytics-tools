<a name="top"></a>

# A List of Prediction Market Analytics Tools You Should Use Before Losing Money

![Maintained](https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-blue.svg)
[![Telegram](https://img.shields.io/badge/Telegram-Predictbook_Analysis-26A5E4?logo=telegram&logoColor=white)](https://t.me/PredictbookAnalysis)

Maintained by [Predictbook](https://predictbook.co): independent market-mechanics analysis for prediction markets, odds, volume, and timing, not headlines. Follow the breakdowns on [X](https://x.com/predictbook) or [Telegram](https://t.me/PredictbookAnalysis), or get real-time move alerts on [Telegram](https://t.me/Predictbook).

A working list of tools for trading, tracking, and researching prediction markets (Polymarket, Kalshi, and others). Each entry covers what it does, what it's best for, who's behind it (where that's actually public), pricing, and phase. Entries are added as they're found. Nothing here is guaranteed to be maintained by its creators, so vet anything you connect a wallet to.

Want all of the tools below in one place? Follow the Predictbook Prediction Market Tools X List (coming soon).
<!-- TODO: replace with the real X list URL once it's created -->

Every tool here gets reviewed monthly to catch dead links, pulled products, and anything that's gone quiet. Flag anything we've missed and we'll get to it.

If this list saves you some digging, a ⭐ on the repo helps more people find it (no pressure either way, the list stays free and open regardless).

## Contents

- [⭐ Featured](#featured): Predictbook's own analysis, front and center.
- [🌐 Cross-Platform Odds Aggregators](#cross-platform-odds-aggregators): compare odds and volume across platforms at once.
- [🤖 Trade Copying & Automation](#trade-copying--automation): mirror or auto-copy other traders' positions.
- [⚡ Trading Terminals & Execution](#trading-terminals--execution): place and manage trades across venues from one interface.
- [📡 Signal & Fair-Value](#signal--fair-value): spot mispriced markets and model-vs-market gaps.
- [🧾 Portfolio, Tax & Journaling](#portfolio-tax--journaling): track your own positions, P&L, and tax records.
- [🔍 Wallet & Trader Analytics](#wallet--trader-analytics): research other traders' wallets and track records.
- [🐋 Alerts & Whale Monitoring](#alerts--whale-monitoring): get pinged on big trades and unusual wallet activity.
- [🧠 Research & Market Discovery](#research--market-discovery): find and dig into markets and data worth watching.
- [☠️ No Longer Maintained](#no-longer-maintained): tools that used to be here, now dead or abandoned.

---

<a name="featured"></a>

## ⭐ Featured

- **[Predictbook](https://predictbook.co)**: Independent analysis of prediction markets focused strictly on mechanics.
  Odds moves, volume spikes, and timing versus the underlying news. No takes, just the numbers.
  - **Best for:** anyone who wants the actual numbers instead of the takes.
  - **Team:** Predictbook (publishes this list).
  - **Follow:** [X](https://x.com/predictbook) · [Telegram (analysis)](https://t.me/PredictbookAnalysis) · [Telegram (alerts)](https://t.me/Predictbook)
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

[↑ Back to top](#top)

---

<a name="cross-platform-odds-aggregators"></a>

## 🌐 Cross-Platform Odds Aggregators

- **[Predictefy](https://predictefy.com/)**: Aggregates and normalizes odds and volume across Polymarket, Kalshi, and other venues into one terminal.
  Built for spotting cross-platform arbitrage without juggling multiple tabs.
  - **Best for:** traders comparing odds across platforms instead of tab-hopping.
  - **Team:** bootstrapped, built by "Tafcir" and co-founders (per their own dev.to post). No external funding disclosed.
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[PredictionHero](https://predictionhero.com/)**: Aggregates live odds across Polymarket, Kalshi, Limitless, Predict.Fun, and Opinion.
  Trending, new, and ending-soon views, plus a "War Index" for markets seeing heavy activity.
  - **Best for:** hunting the widest net for where markets on the same event disagree.
  - **Team:** not publicly listed.
  - **Pricing:** not publicly listed.
  - **Phase:** beta.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

[↑ Back to top](#top)

---

<a name="trade-copying--automation"></a>

## 🤖 Trade Copying & Automation

- **[PolyCopy](https://polycopy.app/)**: Non-custodial Polymarket copy-trading dashboard with an algorithmic "Copy Score."
  Grades traders by category track record rather than raw follower counts, with optional auto-copy bots.
  - **Best for:** picking who to copy based on real category performance, not follower count.
  - **Team:** not publicly listed.
  - **Pricing:** free tier, Premium $30/mo.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Kreo](https://enter.kreo.app/)**: Telegram- and web-based non-custodial copy-trading tool for Polymarket and Kalshi wallets.
  Sub-3-second execution and insider-flow alerts.
  - **Best for:** traders who want fast wallet-copying without a subscription.
  - **Team:** not publicly listed.
  - **Pricing:** flat 0.5% fee, no subscription.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

[↑ Back to top](#top)

---

<a name="trading-terminals--execution"></a>

## ⚡ Trading Terminals & Execution

- **[Kairos](https://kairos.trade/)**: Trading terminal and API across Kalshi, Polymarket, Predict.fun, and Hyperliquid.
  Stacks matching contracts into a single composite order book and routes orders to the best price on any venue. Colocated feeds, sub-second streaming books, market-making and arbitrage strategy templates, backtesting against recorded books, and REST + WebSocket APIs with a free sandbox. Execution round trips in tens of milliseconds (self-reported).
  - **Best for:** heavy cross-venue traders who don't want a separate login for every platform.
  - **Team:** founded by ex-Cboe quants. Raised $2.5M led by a16z crypto with Geneva Trading participating (per a16z crypto and Fortune coverage).
  - **Pricing:** free sandbox, paid tiers not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Stand](https://www.stand.trade/)**: Trading terminal and aggregator for Kalshi and Polymarket with a "counter-trading" feature.
  Auto-fades historically unprofitable wallets instead of following the crowd.
  - **Best for:** traders who'd rather fade known losers than copy winners.
  - **Team:** co-founded by Edward Ridgely (per Finance Magnates and The Defiant coverage). ~$200M annualized volume reported, no public funding disclosed.
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Traderline](https://traderline.com/)**: Free third-party ladder-trading interface with real-time charts and hotkeys.
  Faster order execution on Polymarket and Betfair. Also covers Betfair, not just prediction markets.
  - **Best for:** execution speed over analytics.
  - **Team:** built by Mythical Technologies Lda (Portugal), operating trading software since ~2011 (self-reported).
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Predict Parity](https://predictparity.com/)**: Trade across multiple platforms from one interface while tracking wallet-level PnL.
  Also tracks win rates and "smart money" wallets on Polymarket and Kalshi.
  - **Best for:** traders who want execution and wallet tracking in the same tab.
  - **Team:** not publicly listed (a third-party directory attributes it to "a small New York team," unconfirmed).
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Macropredict](https://macropredict.io/)**: Real-money prediction app covering politics, crypto, sports, and more, with combo betting.
  Stack calls into combos for bigger payouts. $5 minimum per prediction, odds shown in cents, instant cash-out.
  - **Best for:** casual predictors who want a mobile-first, combo-style betting interface.
  - **Team:** not publicly listed (self-disclosed builder in community discussion, not independently confirmed).
  - **Pricing:** free to browse, $5 minimum per prediction.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[River Markets](https://rivermarkets.com/)**: Prime broker for prediction markets, built for professional trading firms.
  Unified execution and risk management across venues. Institutional-focused, not a retail terminal.
  - **Best for:** professional trading firms that need unified execution and risk across multiple venues.
  - **Team:** $8.5M seed round led by Haun Ventures (per River Markets' own X announcement, Aug 2026).
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

[↑ Back to top](#top)

---

<a name="signal--fair-value"></a>

## 📡 Signal & Fair-Value

- **[PMIP](https://pmip.io/)**: Portfolio terminal tracking live spreads, positions, and P&L across Kalshi and Polymarket.
  Resolution-rule analysis and an AI analyst chat built in.
  - **Best for:** spotting mispricing from resolution-rule differences between venues.
  - **Team:** not publicly listed.
  - **Pricing:** not publicly listed.
  - **Phase:** pre-launch.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Alphascope](https://www.alphascope.app/)**: AI research workspace aggregating live odds, news-impact analysis, and probability charts.
  Covers Polymarket, Kalshi, Manifold, and Opinion. Portfolio tracking and automated strategies are listed as "coming soon."
  - **Best for:** traders who want an AI read on whether the news justifies the price.
  - **Team:** not publicly listed.
  - **Pricing:** not publicly listed.
  - **Phase:** live (some features coming soon).
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

[↑ Back to top](#top)

---

<a name="portfolio-tax--journaling"></a>

## 🧾 Portfolio, Tax & Journaling

- **[PredictBoox](https://predictboox.com/)**: Syncs positions, trade history, and P&L from Kalshi and Polymarket into one dashboard.
  Trade journaling and tax-ready export included.
  - **Best for:** keeping tax season simple across multiple platforms.
  - **Team:** not publicly listed.
  - **Pricing:** Pro $19.99/mo, Genius $39.99/mo.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

[↑ Back to top](#top)

---

<a name="wallet--trader-analytics"></a>

## 🔍 Wallet & Trader Analytics

- **[Polysights](https://www.polysights.xyz/)**: Analytics-and-execution platform for Polymarket covering market discovery and insider-wallet detection.
  Includes a trading terminal with API/CLI access.
  - **Best for:** spotting sharp wallets before the price catches up.
  - **Team:** founded by Tre Upshaw. Raised $1.5M backed by Polymarket (per CNBC, June 2026).
  - **Pricing:** not publicly listed.
  - **Phase:** beta.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Polymarket Analytics](https://polymarketanalytics.com/)**: Searchable database of 1M+ Polymarket traders and markets.
  Trader P&L visualization and custom watchlists, refreshed every 5 minutes.
  - **Best for:** digging through the largest historical trader database out there.
  - **Team:** not publicly listed.
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[PolyScalping](https://polyscalping.org/)**: Free, no-signup Polymarket scanner tracking earnings across LP rewards, maker/taker rebates, referrals, and yield.
  Leaderboards and fee calculators included.
  - **Best for:** seeing every reward stream Polymarket's own UI hides.
  - **Team:** two independent developers, "kober" and "d1namit" (per their own X posts). No institutional backing.
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[PredictFolio](https://predictfolio.com/)**: Free analytics platform tracking Polymarket and Kalshi trader PnL, win rates, and market volume and pricing.
  Includes a trader-discovery leaderboard.
  - **Best for:** free multi-platform trader performance tracking.
  - **Team:** operated by ClearCode B.V. (per site footer). No funding disclosed.
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[PolySmartWallet](https://polysmartwallet.com/)**: Real-time leaderboard scoring Polymarket traders by PnL, backtested returns, win rate, and slippage resistance.
  Per-trader profiles and live PnL charts, Polymarket only.
  - **Best for:** a quick no-login leaderboard check, narrower than PredictFolio.
  - **Team:** not publicly listed. Fully anonymous operator.
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Arkham: Polymarket Profitable Traders](https://arkm.com/tags/polymarket-profitable-trader)**: Arkham Intelligence's tag/filter view of Polymarket wallets with positive all-time PnL (realized plus unrealized).
  Not a ranked leaderboard, a filter for "currently profitable" wallets on Arkham's broader on-chain analytics platform.
  - **Best for:** filtering Polymarket wallets down to the ones that are actually profitable right now.
  - **Team:** part of Arkham Intelligence, founded 2020. Raised $12M+ Series A backed by Peter Thiel and Sam Altman (per DL News, CoinCarp).
  - **Pricing:** free to browse.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

[↑ Back to top](#top)

---

<a name="alerts--whale-monitoring"></a>

## 🐋 Alerts & Whale Monitoring

- **[PolymarketScan](https://polymarketscan.org/)**: Free real-time Polymarket analytics tracking whale trades and top traders.
  Alerts pushed via its @PolyWhaleAlerts feed.
  - **Best for:** getting whale alerts on Twitter instead of buried in an app.
  - **Team:** not publicly listed. Appears to be an independent or solo project.
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[PolyWatchDog](https://polywatchdog.com/)**: Real-time Polymarket monitoring with a live dashboard and wallet-level trader search.
  Custom smart alerts (browser and Telegram) plus copy-trade notifications.
  - **Best for:** one tool that covers alerts, trader search, and copy-trade pings.
  - **Team:** not publicly listed. Domain registered February 2026, worth independent vetting before connecting a wallet.
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[PolyAlertHub](https://polyalerthub.com/)**: Real-time Polymarket monitoring delivering smart-money and whale-flow alerts.
  Fresh-wallet and bot-detection signals, plus a paper-trading terminal.
  - **Best for:** whale alerts scored by conviction and win rate, with copy-trade links.
  - **Team:** not publicly listed. (Self-reported win-rate and ROI stats are marketing claims, not verified performance.)
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[yesno.pm](https://yesno.pm/)**: Telegram/Discord/X bot delivering wallet analytics (Sharpe ratio, drawdown, ROI).
  Insider-trade tracking and group leaderboards for Polymarket and Kalshi.
  - **Best for:** tracking trade calls and leaderboards right in your group chat.
  - **Team:** not publicly listed.
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Betmoar](https://www.betmoar.fun/)**: Discord-first trading edge tool: whale and trader tracking, transaction analysis, and a real-time news terminal tagged to markets.
  Describes itself as the official bot provider for Polymarket, with $1B+ in trading volume processed (both self-reported, not independently confirmed).
  - **Best for:** communities that want whale alerts and market news inside Discord instead of a separate app.
  - **Team:** operated by Betmoar Innovation Limited. No further team or funding info disclosed.
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

[↑ Back to top](#top)

---

<a name="research--market-discovery"></a>

## 🧠 Research & Market Discovery

- **[Poly Helper](https://polyhelper.io/)**: Free Chrome/Brave extension embedding 18+ contextual data panels directly into the Polymarket interface.
  Crypto prices, sports scores, macro data, whale tracking, and news, all in-context.
  - **Best for:** researching without leaving the Polymarket tab.
  - **Team:** not publicly listed (a third-party directory attributes it to a small team holding a Polymarket Builders Badge, unconfirmed).
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[METAR.ws](https://metar.ws)**: Real-time WebSocket API streaming aviation weather observations and forecast model data as structured JSON.
  The same underlying data source used to resolve weather-related contracts on Polymarket and Kalshi.
  - **Best for:** checking the real resolution data behind weather markets instead of guessing.
  - **Team:** not publicly listed.
  - **Pricing:** free sandbox tier, paid tiers from €49/mo.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[TickFoundry](https://tickfoundry.com/)**: Archived Polymarket order-book data pulled straight off the live socket, not periodic snapshots.
  Every book update, full L1 and 25-level L2 depth on both sides, trade data, and Polymarket's own sports state feed, continuous since June 21, 2026. Book capture has run since May 11, 2026, and a separate onchain fill layer reaches back further and carries wallet identity the socket data never had. One thing worth knowing: the feeds carry no `condition_id`, so joining scores to books is done by time, not by ID.
  - **Best for:** rebuilding exactly what the order book looked like at any past moment.
  - **Team:** built and run solo, self-disclosed rather than anonymous.
  - **Pricing:** free tier claims 5 market-days of your choosing, no card required. Paid tiers above that.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

[↑ Back to top](#top)

---

<a name="no-longer-maintained"></a>

## ☠️ No Longer Maintained

- **[Poly Prediction](https://polyprediction.app/)**: Surfaced trending Polymarket markets with live odds, volume, and AI-generated analysis tied to the news driving each market.
  Site appears inactive as of August 2026 (left here for reference, not as a live recommendation).
  - **Team:** fully anonymous, never disclosed.
  - **Added:** Aug 2026 · **Removed:** Aug 2026 (site inactive).

[↑ Back to top](#top)

---

Missing a tool, or something here is out of date? This list is maintained by [Predictbook](https://predictbook.co). Reach out and we'll add or fix it.
