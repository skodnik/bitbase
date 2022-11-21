# BitBase

## Just rate

```shell
bash ./bitbase --amount 50 --coin LTC
```

```txt
2022.11.21 20:21:40 UTC+0100

coin  LTC
rate  60.16 eur/LTC

rate  54.144 eur/LTC
swap  50 eur -> 0.748005 LTC

rate  66.8444 eur/LTC
swap  0.923463 LTC -> 50 eur
```

## Rate with rub conversion

```shell
bash ./bitbase --amount 50 --coin LTC --rub 3600 --get 0.9597
```

```text
2022.11.21 20:52:03 UTC+0100

rate  3751.17 rub/LTC
swap  3600 rub -> 0.9597 LTC

coin  LTC
rate  59 eur/LTC
rate  63.5792 rub/eur

rate  53.1 eur/LTC
swap  50 eur -> 0.762712 LTC

rate  65.5556 eur/LTC
rate  70.6435 rub/eur
swap  0.94162 LTC -> 50 eur
```

## Available coins

```text
BTC, ETH, BTBS, USDT, GQ, ADA, DOT, WOOP, 
DOGE, LTC, BCH, XLM, VET, UNI, NEO, BTT, 
CHZ, SOL, ALGO, ATOM, XTZ, VTHO, TRX, XRP 
```