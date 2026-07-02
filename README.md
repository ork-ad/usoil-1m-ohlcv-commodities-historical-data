# USOIL 1m OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-5_622_739_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)]() [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full USOIL dataset on ork.ad**](https://ork.ad/)

**USOIL 1m OHLCV Commodities historical data** — ultra high-quality one-minute OHLCV for **WTI Crude Oil**. Extended-session energy and industrial metals — beyond US cash hours. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1-minute OHLCV** for **WTI Crude Oil** (Commodities)
- **Extended-session energy and industrial metals — beyond US cash hours**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m` only) · **13 timeframes** on [ork.ad](https://ork.ad/) · **5,622,739** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `USOIL_1m.csv` (171,581 rows, `2025-12-26` → `2026-06-26`). **Full archive on [ork.ad](https://ork.ad/)** — **5,622,739** `1m` rows (~267.65 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2009-03-11` → `2026-06-26`.

## Download sample

**[USOIL_1m.csv](https://github.com/ork-ad/usoil-1m-ohlcv-commodities-historical-data/blob/main/USOIL_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/usoil-1m-ohlcv-commodities-historical-data/main/USOIL_1m.csv)) · [GitHub Releases](https://github.com/ork-ad/usoil-1m-ohlcv-commodities-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/usoil-1m-ohlcv-commodities-historical-data/](https://ork-ad.github.io/usoil-1m-ohlcv-commodities-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | WTI Crude Oil · Commodities | WTI Crude Oil · Commodities |
| Timeframes | `1m` only (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1m rows | 171,581 | **5,622,739** |
| Size | 8.75 MB | ~267.65 MB |
| Period | `2025-12-26` → `2026-06-26` | `2009-03-11` → `2026-06-26` |
| File | `USOIL_1m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **1-minute (`1m`) evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub 1m samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USOIL_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-12-26T20:44:00Z | 56.839 | 56.847 | 56.833 | 56.833 | 18 |
| 2025-12-26T20:45:00Z | 56.833 | 56.834 | 56.819 | 56.832 | 17 |
| 2025-12-26T20:46:00Z | 56.832 | 56.864 | 56.832 | 56.858 | 10 |
| 2025-12-26T20:47:00Z | 56.858 | 56.863 | 56.848 | 56.852 | 14 |
| 2025-12-26T20:48:00Z | 56.852 | 56.867 | 56.852 | 56.857 | 8 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-26T20:40:00Z | 69.701 | 69.733 | 69.651 | 69.657 | 223.00 |
| 2026-06-26T20:41:00Z | 69.657 | 69.713 | 69.567 | 69.685 | 195.00 |
| 2026-06-26T20:42:00Z | 69.685 | 69.847 | 69.673 | 69.729 | 213.00 |
| 2026-06-26T20:43:00Z | 69.729 | 69.796 | 69.69 | 69.733 | 192.00 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('USOIL_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USOIL_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('USOIL_1m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **USOIL** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **5,622,739** rows at `1m`, plus all higher timeframes in the same ZIP.

**[→ Get the full USOIL dataset on ork.ad](https://ork.ad/)**

---
*GetData · USOIL 1m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-02 UTC*