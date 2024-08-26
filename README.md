# Back-Testing

PizzaPickle - 고객과 PB를 연결시켜주는 온라인 화상 서비스 및 매매시스템의 백테스팅 서버

### 국내 요청 예시

```json
{
  "start_from_latest_stock": "false",
  "portfolio": {
    "stock_list": [
      ["133690", "TIGER 미국나스닥100", 0.25, "false"],
      ["381180", "TIGER 미국필라델피아반도체나스닥", 0.25, "false"],
      ["005930", "삼성전자", 0.5, "false"]
    ],
    "balance": 1000000,
    "interval_month": 1,
    "start_date": "20100101",
    "end_date": "20221231"
  }
}
```

### 해외 요청 예시

```json
{
  "start_from_latest_stock": "false",
  "portfolio": {
    "stock_list": [
      ["AAPL", "Apple", 0.25, "true"],
      ["NVDA", "NVIDIA", 0.25, "true"],
      ["TSLA", "Tesla", 0.5, "true"]
    ],
    "balance": 1000000,
    "interval_month": 1,
    "start_date": "20100101",
    "end_date": "20221231"
  }
}
```
