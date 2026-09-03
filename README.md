# UKOIL 1m OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-5_237_943_rows-blue)](https://getdata.finance/datasets/ukoil) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ukoil)

### -> [**Download the full UKOIL dataset on getdata.finance**](https://getdata.finance/datasets/ukoil)

**UKOIL 1m OHLCV commodities historical data** — ultra high-quality 1m OHLCV for **Brent Crude Oil**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Brent Crude Oil** (Commodities)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/ukoil) · **5,237,943** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `UKOIL_1m.csv` (55,440 rows, `2026-07-01` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/ukoil)** — **5,237,943** `1m` rows, **11 timeframes**, `2010-02-01` -> `2026-09-02`.

## Download sample

**[UKOIL_1m.csv](https://github.com/getdata-finance/ukoil-1m-ohlcv-commodities-historical-data/blob/main/UKOIL_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ukoil-1m-ohlcv-commodities-historical-data/main/UKOIL_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ukoil))** |
|---|--:|---|
| Instrument | Brent Crude Oil · Commodities | Brent Crude Oil · Commodities |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **5,237,943** |
| Period | `2026-07-01` -> `2026-09-02` | `2010-02-01` -> `2026-09-02` |
| File | `UKOIL_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ukoil) |
| Coverage report | — | [UKOIL coverage](https://getdata.finance/coverage/ukoil) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ukoil)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`UKOIL_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-01T17:26:00+00:00 | 71.316 | 71.346 | 71.314 | 71.325 | 55 |
| 2026-07-01T17:27:00+00:00 | 71.325 | 71.341 | 71.31 | 71.335 | 38 |
| 2026-07-01T17:28:00+00:00 | 71.335 | 71.355 | 71.334 | 71.355 | 29 |
| 2026-07-01T17:29:00+00:00 | 71.355 | 71.366 | 71.344 | 71.365 | 22 |
| 2026-07-01T17:30:00+00:00 | 71.365 | 71.366 | 71.325 | 71.354 | 63 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 96.115 | 96.15 | 96.04 | 96.096 | 233 |
| 2026-09-02T01:57:00+00:00 | 96.096 | 96.126 | 96.065 | 96.094 | 257 |
| 2026-09-02T01:58:00+00:00 | 96.094 | 96.096 | 95.966 | 95.99 | 250 |
| 2026-09-02T01:59:00+00:00 | 95.99 | 96.019 | 95.924 | 95.974 | 246 |
| 2026-09-02T02:00:00+00:00 | 95.974 | 95.985 | 95.944 | 95.97 | 114 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full UKOIL archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full UKOIL dataset on getdata.finance](https://getdata.finance/datasets/ukoil)**
