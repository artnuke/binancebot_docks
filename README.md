# Some very smart title here

#### Welcome to binance bot! We are here to scam you!

All commands start with "/" and follwed by argumetns. They can be represented by formula:

```
/command arg1 arg2 ... argN
```

### :warning: Important :warning:

Date formats: 

1. nY - n Years (max 2)
2. nM - n Mounths

Example:

```
/exchange_rate BTC 1Y
```

### List of avalable commands:
 - /exchange_rate token period - Procces data in given period and returns graph of given token exchange rate.
 - /tokens  - Lists all avalible tokens
 - /basebtc currency1 to currency2 - Links two currency throught BTC and compares them with exchange rate based on USD.
 - /corr_matrix - Draws correlation matrix of all available curencies

## User tips and shortcuts
#### 1) Token shortcut

Token argument can also be specified as correspondent number in list.

  For example:

 1. Lets list tokens 
  ```
  /tokens
  ```
  Output
  ```
  Available tokens 
--------------------
1  -  BTC/USD
2  -  ETH/USD
3  -  LTC/USD
  ```
2. Now we can execute command /exchange_rate using following syntaxes
```
/exchange_rate 1 1Y
```

2. Default period is 1 year if it is what you want you dont need to specify it

```
/exchange_rate BTC 1Y -> /exchange_rate BTC
```
 
