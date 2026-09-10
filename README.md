# JPN225 5m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_121_004_rows-blue)](https://getdata.finance/datasets/jpn225) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/jpn225)

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
- **Free evaluation sample** on GitHub (`5m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/jpn225) · **1,121,004** `5m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `5m` sample updated in sync

> **Sample on GitHub** · `JPN225_5m.csv` (35,754 rows, `2026-03-10` -> `2026-09-09`, 2.39 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/jpn225)** — **1,121,004** `5m` rows (full `1m`: 4,718,919), **11 timeframes**, `2008-09-01` -> `2026-09-09`.

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
| 5m rows | 35,754 | **1,121,004** |
| Size | 2.39 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/jpn225) |
| Period | `2026-03-10` -> `2026-09-09` | `2008-09-01` -> `2026-09-09` |
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
| 2026-03-10T18:35:00+00:00 | 55099.36 | 55164.36 | 54969.85 | 55024.85 | 1428 |
| 2026-03-10T18:40:00+00:00 | 55024.85 | 55034.36 | 54914.86 | 54914.86 | 1155 |
| 2026-03-10T18:45:00+00:00 | 54914.86 | 55014.36 | 54914.84 | 54979.34 | 877 |
| 2026-03-10T18:50:00+00:00 | 54979.34 | 55064.36 | 54914.84 | 54979.35 | 720 |
| 2026-03-10T18:55:00+00:00 | 54979.35 | 54999.36 | 54914.86 | 54929.34 | 795 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-09T01:40:00+00:00 | 65629.49 | 65629.49 | 65504.49 | 65504.5 | 313 |
| 2026-09-09T01:45:00+00:00 | 65504.5 | 65559.51 | 65494.51 | 65519.51 | 254 |
| 2026-09-09T01:50:00+00:00 | 65519.51 | 65519.51 | 65394.49 | 65399.51 | 232 |
| 2026-09-09T01:55:00+00:00 | 65399.51 | 65491.51 | 65384.49 | 65489.5 | 280 |
| 2026-09-09T02:00:00+00:00 | 65489.5 | 65554.01 | 65474.49 | 65534.51 | 169 |

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

The complete **JPN225** archive on **[getdata.finance](https://getdata.finance/datasets/jpn225)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,121,004** rows at `5m`, plus all other timeframes in the same ZIP.

**[-> Get the full JPN225 dataset on getdata.finance](https://getdata.finance/datasets/jpn225)**

---
*GetData · JPN225 5m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/jpn225)*
