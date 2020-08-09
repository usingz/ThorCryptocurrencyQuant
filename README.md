# ThorCryptoCurrency Strategy Library

<br>
<br>
<p align="center">
  <img src ="http://thorquant.com/Thor-Quant.png"/>
</p>
<br>
<br>

 * Thor Strategy Library策略可运行的数字货币交易所（其他交易所也可适配后运行）

        * BitMEX ：数字货币期货、永续合约

        * Bybit ：数字货币永续合约

        * Binance ：数字货币现货

        * Binance永续 ：数字货币永续合约

        * OKEX ：数字货币现货

        * OKEX永续 ：数字货币永续合约

        * OKEX期货 ：数字货币期货

        * Huobi ：数字货币现货

        * Huobi期货 ：数字货币期货

        * Huobi永续 ：数字货币永续 

        * Bitfinex ：数字货币现货

        * Coinbase ：数字货币现货

        * Bitstamp ：数字货币现货


## 策略介绍

- 平衡策略：

- 高频网格策略：

- 吃针策略：

- Boll指标策略：

- 对敲策略：

- 套利策略：



## 使用说明

- 所有策略开箱即用，填写自己的APIKey 与 Sercet，填写参数运行即可
- 每种策略有不同对应交易所，同一策略根据命名区分交易所，运行时注意查看
- 主流交易所借助CCXT实现，非主流交易所也适配封装了所有公有私有API，可直接运行
- 非主流交易所数据格式返回与CCXT数据格式一致，方便数据分析
- 运行环境Python3,CCXT需自行安装（pip install ccxt）
- JavaScript策略基于FMZ运行（原botvs）



## 贡献代码

ThorCryptoCurrency Strategy Library使用Github托管其源代码，如果希望贡献代码请使用github的PR（Pull Request）的流程:

1. [创建 Issue](https://github.com/fengok/ThorCryptocurrencyQuant/issues/new) - 对于策略较大的改动（如新功能，重构等）最好先开issue讨论一下，较小的improvement（如文档改进等）直接发PR即可

2. Fork [ThorCryptocurrencyQuant](https://github.com/fengok/ThorCryptocurrencyQuant) - 点击右上角**Fork**按钮

3. Clone你自己的fork: ```git clone https://github.com/fengok/ThorCryptocurrencyQuant.git```
	* 如果你的fork已经过时，需要手动sync：[同步方法](https://help.github.com/articles/syncing-a-fork/)

4. 从**dev**创建你自己的feature branch: ```git checkout -b $my_feature_branch dev```

5. 在$my_feature_branch上修改并将修改push到你的fork上

6. 创建从你的fork的$my_feature_branch分支到主项目的**dev**分支的[Pull Request] -  [在此](https://github.com/fengok/ThorCryptocurrencyQuant/compare?expand=1)点击**compare across forks**，选择需要的fork和branch创建PR

7. 等待review, 需要继续改进，或者被Merge!



## 项目捐赠

过去2年中在国内的社区有偿无偿帮助很多用户写过数字货币策略，最近打算把这两年中的积累开源放出来，并在后续进行更新维护，非常感谢用户的认可与肯定并进行捐赠，
所有捐赠都会投入到策略库的完善之中，用于支持与壮大数字货币量化的发展！

先强调一下：**本项目里面的策略都是开源的，可以无偿免费使用，并没有强制捐赠的要求！！！**

捐赠方式：支付宝block@163.com（*裕峰）

我们会长期维护捐赠清单，请在捐赠时备注项目名称与捐赠人姓名


## 版权说明

MIT
