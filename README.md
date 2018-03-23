# Exchange_Rate_Crawler

### 資料表結構 currency_spot_usd

```sql
伺服器版本: 10.1.21-MariaDB
資料庫： `exchange_rate`
```

### 資料表結構 currency_spot_usd

```sql
`_id` int(11) NOT NULL,
`時間` datetime NOT NULL,
`現金匯率-本行買入` float NOT NULL,
`現金匯率-本行賣出` float NOT NULL,
`即期匯率-本行買入` float NOT NULL,
`即期匯率-本行賣出` float NOT NULL
```