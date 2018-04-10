# Exchange_Rate_Crawler

用Python寫的匯率爬蟲，爬取目標為**臺灣銀行牌告匯率**的美金匯率，請用jupyter notebook打開

### 資料庫資訊

```sql
伺服器版本: 10.1.21-MariaDB
資料庫： `exchange_rate`
```

### 資料表結構

```sql
資料表結構 `currency_spot_usd`
`_id` int(11) NOT NULL,
`時間` datetime NOT NULL,
`現金匯率-本行買入` float NOT NULL,
`現金匯率-本行賣出` float NOT NULL,
`即期匯率-本行買入` float NOT NULL,
`即期匯率-本行賣出` float NOT NULL
```
