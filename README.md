# Paxful 交易流程以及逻辑梳理

[paxful](https://paxful.com/)，是全球最大虚拟币OTC交易平台，支持不同的国家货币，网络钱包，礼品卡和常见虚拟币的兑换。平台中亚非拉国家的用户最多。中国用户比较少，其中非洲和亚洲以及拉丁美洲小国家的人较多（这里，注意，他们的本国货币汇率极为不稳定，很多小国家的人都想吧自己的货币变成美金，这个地方就是我们的机会。他们的国家有官方汇率和地下汇率两种方式。拿斯里兰卡举例。 比如 LKRUSD=30 (官方报价），黑市报价 LKRUSDT=50。那么该国家的人可以使用 LKR收USD 然后将 USD换成USDT 再换成LKR的方式获得套利收益）这里就是我们的机会。我们提供 USD USDT的兑换服务。

---

## 如何参与

**所需工具**：网络钱包派安应。[Payoneer](https://payoneer.com) 国内外贸用户用得比较多：一般外贸出口企业通过PAYONEER的支付方式收取美金，然后再将美金提现成CNY到自己的银行账户，**绝不收取个人所得税，可放心使用**；PAYONEER的使用方式参见：[网友整理的使用方式](https://www.investitans.com/payoneer-guide/)，可能需要翻墙访问🚧，请自行学会科学上网访问。

## 交易流程

- 首先为PAXFUL账户冲入USDT
- 设置PAXFUL的买单，USD换USDT
- 等待客户购买
- 客户开单，告诉客户PAYONEER EMAIL和转账详情description
- 客户付款后索要截图
- 我方确认到账后放币

---

## 利润计算

一般来说，我们挂单的价格师 1.03 USD 换 USD
其中PAXFUL会抽走1%的手续费。所以我们的实际收到的USD为1.02
我们用1单位的USDT换成了 1.02单位的USD
USDT在国内的汇率目前为，6.53
USD的提现汇率师6.58
那么一轮下来，利润为 (6.58*1.02-6.53)/6.53 大概3%个点
相当于满仓买了个每天3%涨幅的ETF基金。哈哈

---

## 会计报表记账方式

- [x] 🎉 加入[谷歌表格](https://docs.google.com/spreadsheets/d/1kYAovMqiIxYbl9qkeVTy0JN67iD7fxBPrE1RA8dw-JE/edit?usp=sharing)
- [x] 每发生一次状态变化记一次帐目有限自动机类似；
- [x] 🍀 一共有**人民币账户**、**PAXFUL账户**、**交易所账户**、**派安盈账户**；
- [x] 🏁 每发生一次交易记录一行，改变状态，计算利润；
- [x] 💃🏻 每次记账考虑到费率；
- [x] 🚑 我们最终利润按U本文计算；
- [x] 📝 一个月结算一次；分红按日，周，月。你们随意
- [x] 🛠 分红方式(**4,3,3**)，值班方式，8-8-8
- [x] ✨ 我每天复合交易报表；
- [x] ✨ 阿耀负责国内买U流程和交易；
- [x] 👏 小王负责高阶套利机会发现和PAXFUL交易；
- [x] 🦑 关注时事汇率。国际国内[汇率关注网站](https://www.investopedia.com/)；
- [x] 🌟 特别注意 巴基斯坦，斯里兰卡，阿根廷，尼日利亚汇率。和美元兑人民币汇率；（客户大部分来自以上国家）

---

## 高阶玩法

$$
ETH BTC 和各国法币之间的兑换。为了防止价格暴跌，需要打对冲。做空 做多。
关注宏观经济，关注美联储货币政策，加息周期。推荐 APP。 金十数据
$$

---

## PAXFUL规则和PAYONEER规则

第一，PAXFUL不要请求线下交易
第二，PAYONEER拒绝银行卡资金，ONLY ACCEPT PAYONEER BALANCE
第三，PAYONEER 不要多个IP登录。
第四，自行学习

