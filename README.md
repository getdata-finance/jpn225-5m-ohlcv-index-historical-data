# JPN225 5m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_123_758_rows-blue)](https://getdata.finance/datasets/jpn225) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/jpn225)

### -> [**Download the full JPN225 dataset on getdata.finance**](https://getdata.finance/datasets/jpn225)

**JPN225 5m OHLCV index historical data** — ultra high-quality 5m OHLCV for **Nikkei 225**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 5m OHLCV** for **Nikkei 225** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`5m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/jpn225) · **1,123,758** `5m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `5m` sample updated in sync

> **Sample on GitHub** · `JPN225_5m.csv` (36,225 rows, `2026-03-23` -> `2026-09-23`, 2.41 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/jpn225)** — **1,123,758** `5m` rows (full `1m`: 4,718,919), **11 timeframes**, `2008-09-01` -> `2026-09-23`.

## Download sample

**[JPN225_5m.csv](https://github.com/getdata-finance/jpn225-5m-ohlcv-index-historical-data/blob/main/JPN225_5m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/jpn225-5m-ohlcv-index-historical-data/main/JPN225_5m.csv)) · [GitHub Releases](https://github.com/getdata-finance/jpn225-5m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/jpn225-5m-ohlcv-index-historical-data/](https://getdata-finance.github.io/jpn225-5m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/jpn225](https://getdata.finance/datasets/jpn225)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/jpn225))** |
|---|--:|---|
| Instrument | Nikkei 225 · Index | Nikkei 225 · Index |
| Timeframes | `5m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 5m rows | 36,225 | **1,123,758** |
| Size | 2.41 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/jpn225) |
| Period | `2026-03-23` -> `2026-09-23` | `2008-09-01` -> `2026-09-23` |
| File | `JPN225_5m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/jpn225) |
| Coverage report | — | [JPN225 coverage](https://getdata.finance/coverage/jpn225) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`5m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/jpn225)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `5m` sample · [getdata.finance](https://getdata.finance/datasets/jpn225) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `5m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`JPN225_5m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-23T02:30:00+00:00 | 51457.29 | 51457.29 | 51367.81 | 51382.8 | 385 |
| 2026-03-23T02:35:00+00:00 | 51382.8 | 51412.29 | 51282.79 | 51282.79 | 313 |
| 2026-03-23T02:40:00+00:00 | 51282.79 | 51377.3 | 51257.81 | 51307.81 | 337 |
| 2026-03-23T02:45:00+00:00 | 51307.81 | 51327.79 | 51242.81 | 51247.8 | 329 |
| 2026-03-23T02:50:00+00:00 | 51247.8 | 51317.29 | 51217.81 | 51277.8 | 264 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-23T01:40:00+00:00 | 66837.49 | 66842.49 | 66788 | 66793 | 180 |
| 2026-09-23T01:45:00+00:00 | 66793 | 66847.51 | 66787.99 | 66823.01 | 254 |
| 2026-09-23T01:50:00+00:00 | 66823.01 | 66832.51 | 66798.01 | 66812.49 | 225 |
| 2026-09-23T01:55:00+00:00 | 66812.49 | 66823 | 66797.99 | 66808 | 170 |
| 2026-09-23T02:00:00+00:00 | 66808 | 66842.99 | 66803 | 66833.01 | 24 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('JPN225_5m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('JPN225_5m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('JPN225_5m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='5min')
print(pf.stats())
```

## Download full data

The complete **JPN225** archive on **[getdata.finance](https://getdata.finance/datasets/jpn225)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,123,758** rows at `5m`, plus all other timeframes in the same ZIP.

**[-> Get the full JPN225 dataset on getdata.finance](https://getdata.finance/datasets/jpn225)**

---
*GetData · JPN225 5m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/jpn225)*
