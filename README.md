# atomicals-command
atomicals-command to mint dft

## run create wallet(具体以下载的文件名为准)
### windwos
```
x86_64-pc-windows-gnu-atomicals-command.exe wallet-init
```
### macbook M系列芯片(具体以下载的文件名为准)
```
aarch64-apple-darwin-atomicals-command wallet-init
```

## run mint dft(具体以下载的文件名为准)
### windwos x86_64
```sh
x86_64-pc-windows-gnu-atomicals-command.exe
```
### macbook M系列芯片(具体以下载的文件名为准)
```
aarch64-apple-darwin-atomicals-command
```
##### 此脚本默认收取 币种锁仓价值30%的satoshi作为手续费，如quark为20000，收取6000 satoshi，在reveal交易中自动扣除，不额外转账产生矿工费
##### 初次运行脚本时，请新建一个 wallets 文件夹与脚本在同一目录
##### 脚本名 wallet-init 为创建钱包。 初次运行时，请先创建钱包。 可生成多个地址，或根据.env中WALLET_FILE  生成，重名文件会自动加后缀，不会覆盖文件。
##### wallet.json中 primary address可随时修改，可不填私钥，此地址为mint到token的收款地址。
##### wallet.json中 funding address不可修改，mint前，请往此地址转入足额btc。 wif为钱包私钥，导入其他钱包软件使用。

##### 手续费会根据实际情况调整， 如需调低手续费请提交issues联系 其他事宜也请提交issues联系