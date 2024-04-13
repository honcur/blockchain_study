# 1 了解区块链,Bitcoin , Ethereum
**目标:** 了解 一下这些技术产生的背景已经解决了什么问题。

##  1.1什么是区块链

参考链接1 [区块链是什么通俗解释](https://zhuanlan.zhihu.com/p/346493198)

参考链接2 [什么是区块链](https://aws.amazon.com/cn/what-is/blockchain/?aws-products-all.sort-by=item.additionalFields.productNameLowercase&aws-products-all.sort-order=asc)

##  1.2什么是Bitcoin

参考链接1 [什么是bitcoin](https://bitcoin.org/zh_CN/faq#who-controls-the-bitcoin-network)  

参考链接1 [官方](https://bitcoin.org/)  有时间可以看下官网的白皮书

## 1.3什么是Ethereum

参考链接1 [什么是Ethereum](https://ethereum.org/zh/what-is-ethereum/)

参考链接2 [智能合约](https://ethereum.org/zh/smart-contracts/)  Ethereum相比Bitcoin很重要的创新就是智能合约

参考链接3 [官方](https://ethereum.org/)  有时间可以看下官网的白皮书

参考链接3 [Bticoin与Ethereum异同](https://www.investopedia.com/articles/investing/031416/bitcoin-vs-ethereum-driven-different-purposes.asp)

## 1.4 其他常见区块链网络
我们穷人一般都不会使用Bitcoin、Ethereum,它们俩交易手续费太高了。常用的其他区块链网络有:
- arbitrum, optimism,BNB Chain,polygon(ethereum系网络)
- Solana,Trx 等

# 2 钱包

**钱包网络介绍:** 
从上一章可以看到现在有很多的区块链网络，按道理来说不同的区块链网络应该使用不同的协议，也应该有多个不同钱包软件。但实际上我们有Metamask,TokenPocket这两个钱包已经能满足我们。这里主要有两个原因，第一个原因是很多网络都基于ethereum或者符合ethereum规范，这些区块链网络的钱包和ethereum是通用的，Metamsk是以太坊钱包就适用于这些所有的网络；第二个原因是像TokenPocket这类钱包软件它们写了不同协议代码来满足各类区块链网络，自然就能支持各种网络。

**目标:** 安装并使用常见钱包如Metamask,TokenPocket。操作如下功能:

- 创建钱包账户
- 切换钱包网络
- 更改钱包RPC地址
- 钱包之间转账

# 3 了解并使用常见金融产品1(中心化)
## 3.1 加密货币交易所
**目标:**  注册一家常见交易所，如[币安](https://binance.com)、[欧易](https://www.okx.com/)等，了解常见金融产品以及功能:

- C2C法币购买加密货币
- C2C出售加密货币
- 通过钱包充值加密货币
- 从交易所提现加密货币到钱包
- 现货交易
- 合约交易

# 4 了解常见金融产品2(去中心化)
## 4.1 去中心化交易所 Uniswap3

  **地址:**  [Uniswap](https://app.uniswap.org/)

  **目标:**  通过Uniswap3了解或完成以功能:

- 兑换虚拟货币
- 添加流动新

## 4.2 Aave借贷协议

  **地址:**  [Aave](https://app.aave.com/)

  **目标:**  通过 Aave了解或完成以功能:

 - 质押代币
 - 借贷ETH

# 5 编程技能学习

## 5.1 Ethereum合约开发

**目标:** 学习solidity合约开发语言以及相关框架工具

- solidity 语言，可以查看[尚硅谷区块链](https://www.bilibili.com/video/BV1NJ411D7rf/?spm_id_from=333.337.search-card.all.click)
- Foundry 框架(主要用于测试)，[Foundry](https://book.getfoundry.sh/)
- hardhat 工具(用于部署)

## 5.2 Ethereum合约源码学习 

**目标:** 学习uniswapV2,uniswapV2Lp质押和uniswapV3源码

- uniswapV2源码 [v2-core](https://github.com/Uniswap/v2-core) 、[v2-periphery](https://github.com/Uniswap/v2-periphery)、[uniswapV2Lp质押](https://github.com/pancakeswap/pancake-smart-contracts/blob/master/projects/farms-pools/contracts/SmartChef.sol)
- uniswapV3源码 [v3-core](https://github.com/Uniswap/v3-core)、[v3-periphery](https://github.com/Uniswap/v3-periphery)

# 6.  安全

google 搜索链上常见攻击和攻击案例
