# 开发合约
在 `contracts` 目录下编写合约

# 编译
```
$ truffle compile

Compiling your contracts...
===========================
> Compiling ./contracts/ConvertLib.sol
> Compiling ./contracts/MetaCoin.sol
> Compiling ./contracts/Migrations.sol
> Artifacts written to /Users/linjingjing/Documents/project/MetaCoin/build/contracts
> Compiled successfully using:
   - solc: 0.8.13+commit.1d4f565a.Emscripten.clang
```
# 部署脚本
在 migrations 下面添加部署脚本

# 发布
在 truffle-config.js 文件里替换私钥,设置可选网络,
执行命令
```
$ truffle migrate --network weelink   
```

参考链接: https://trufflesuite.com/docs/truffle/quickstart/