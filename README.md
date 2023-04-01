# DAPP ERC20 USDT SWAP GAME

website: https://dapp-erc20-usdt-swap.vercel.app/

这个项目实现了一种可以用 USDT 交换 Token 的机制。

具体来说，这个合约允许用户使用 USDT 购买 Token，并且用户可以指定一个交换地址来接收 Token。合约中有多个钱包地址，每个钱包地址都有一个最大交换数量和一个价格。

如当前项目即设定六个钱包作为兑换池，设定了相应的价格和兑换量。

当用户购买 Token 时，合约会检查当前钱包是否有足够的 Token 可供出售，如果有，则会将用户的 USDT 转移到收款人账户，并将 Token 转移到用户的钱包地址。

这个合约的玩法可以是作为一种交易平台，用户可以在这里使用 USDT 购买 Token，并在需要时出售这些 Token 获得利润。

此外，合约还可以在一些 Dapp 中使用，例如游戏、社交媒体等，用户可以使用 Token 进行虚拟物品的交换或者在社交媒体上奖励其他用户。

总的来说，这个合约提供了一种简单方便的机制，让用户可以使用 USDT 获得更多的 Token。

