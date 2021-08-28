本文内容来自[introducing wrapped hns](https://www.namebase.io/blog/introducing-wrapped-hns/)，不是全文翻译，只选取我感兴趣的记录&翻译

# 介绍Wrapped HNS

> WHNS给Handshake带来极大的流动性和DeFi

 内容如下：

1. 介绍
2.   WHNS blind loans（WHNS盲贷）
3. 这是如何运行的

## 介绍

Handshake社区正在发展。已经激活的handshake names的数量增长了10倍超过了10万个。

总之就是：hns因其特殊性，目前只能在小交易所和namebase上交易。所以为了让广大的新人和爱好者方便交易。他们搞了个wrapped handshake

Wrapped HNS (WHNS) is an ERC20 token backed 1:1 with HNS.

大概意思就是WHNS是ERC20代币，与HNS 1:1，这将会给Handshake带来极大的流动性。
然后现在在[Uniswap](https://app.uniswap.org/#/swap?inputCurrency=ETH&outputCurrency=0xa771b49064da011df051052848477f18dba1d2ac)已经有个pool给WHNS。
按照他们的说预估会有更多的DEX加入。即使是中心化交易所也更容易通过WHNS来让他们的客户接触Handshake，因为ERC20代币比自定义代币要容易的多。

反正就是通过WHNS，大家可以动过DeFi，靠借出代币产生收益赚钱啦！比如什么Aave和Compound（WHNS还没上Aave和Compound）

## WHNS blind loans （WHNS盲贷）
HNS blind loans
One new capability we're especially excited about is using WHNS loans for blinds to fend off snipers. Through a loaning protocol, a user could:
- Borrow WHNS with ETH to use as a blind
- Unwrap their WHNS on Namebase
- Bid with a blind made much larger via their WHNS loan
- Win their auction
- Re-wrap their HNS blind
- Return their WHNS to receive the collateral back

这段不想翻译

## 这是如何运行的

1. 添加WHNS到以太坊钱包（Metamask，Coinbase等）
2. 合约地址：0xa771b49064da011df051052848477f18dba1d2ac
3. 或者直接在[Uniswap](https://app.uniswap.org/#/swap?inputCurrency=ETH&outputCurrency=0xa771b49064da011df051052848477f18dba1d2ac)上购买WHNS

如果你现在持有HNS，并希望将其转换为WHNS，请发送电子邮件到`whns@namebase.io`,目前没有保证费用
如果你持有WHNS，并希望将其转为HNS，请发送电子邮件到`whns@namebase.io`，他们会在7-14个工作日内为你unwrap，目前没有拆包费用
