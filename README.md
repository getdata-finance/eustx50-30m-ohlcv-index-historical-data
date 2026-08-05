# EUSTX50 30m OHLCV Stock index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-99_080_rows-blue)](https://getdata.finance/datasets/eustx50) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eustx50)

### -> [**Download the full EUSTX50 dataset on getdata.finance**](https://getdata.finance/datasets/eustx50)

**EUSTX50 30m OHLCV stock index historical data** — ultra high-quality 30m OHLCV for **Euro Stoxx 50**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 30m OHLCV** for **Euro Stoxx 50** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eustx50) · **99,080** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `EUSTX50_30m.csv` (3,646 rows, `2026-01-27` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/eustx50)** — **99,080** `1m` rows (~7.12 MB), **11 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W), `2012-08-27` -> `2026-07-31`.

## Download sample

**[EUSTX50_30m.csv](https://github.com/getdata-finance/eustx50-30m-ohlcv-index-historical-data/blob/main/EUSTX50_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eustx50-30m-ohlcv-index-historical-data/main/EUSTX50_30m.csv)) · [GitHub Releases](https://github.com/getdata-finance/eustx50-30m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eustx50-30m-ohlcv-index-historical-data/](https://getdata-finance.github.io/eustx50-30m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eustx50](https://getdata.finance/datasets/eustx50)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eustx50))** |
|---|--:|---|
| Instrument | Euro Stoxx 50 · Stock index | Euro Stoxx 50 · Stock index |
| Timeframes | `30m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 3,646 | **99,080** |
| Size | 0.33 MB | ~7.12 MB |
| Period | `2026-01-27` -> `2026-07-31` | `2012-08-27` -> `2026-07-31` |
| File | `EUSTX50_30m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eustx50) |
| Coverage report | — | [EUSTX50 coverage](https://getdata.finance/coverage/eustx50) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`30m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eustx50)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

GitHub = `30m` sample · [getdata.finance](https://getdata.finance/datasets/eustx50) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EUSTX50_30m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-01-27T18:00:00+00:00 | 5989.11 | 5991.13 | 5985.11 | 5990.12 | 164.1448639157 |
| 2026-01-27T18:30:00+00:00 | 5990.12 | 5993.13 | 5989.11 | 5992.13 | 125.4786407767 |
| 2026-01-27T19:00:00+00:00 | 5992.13 | 5997.13 | 5991.11 | 5997.11 | 111 |
| 2026-01-27T19:30:00+00:00 | 5997.11 | 5999.12 | 5995.11 | 5996.13 | 80.2864528914 |
| 2026-01-27T20:00:00+00:00 | 5996.13 | 6000.62 | 5995.11 | 5995.12 | 86 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T17:30:00+00:00 | 6478.16 | 6478.16 | 6468.65 | 6470.65 | 466 |
| 2026-07-31T18:00:00+00:00 | 6470.65 | 6476.67 | 6469.65 | 6475.17 | 359 |
| 2026-07-31T18:30:00+00:00 | 6475.17 | 6475.65 | 6469.65 | 6471.16 | 201 |
| 2026-07-31T19:00:00+00:00 | 6471.16 | 6479.67 | 6467.65 | 6475.65 | 355 |
| 2026-07-31T19:30:00+00:00 | 6475.65 | 6484.67 | 6467.15 | 6469.2 | 509 |

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

df = pd.read_csv('EUSTX50_30m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EUSTX50_30m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('EUSTX50_30m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **EUSTX50** archive on **[getdata.finance](https://getdata.finance/datasets/eustx50)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **99,080** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full EUSTX50 dataset on getdata.finance](https://getdata.finance/datasets/eustx50)**

---
*GetData · EUSTX50 30m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eustx50) · 2026-08-05 UTC*
