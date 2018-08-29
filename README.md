# Welcome to EOS2FO

首先庆祝FIBOS上线，可以直接使用JavaScript来做开发，相比EOS目前只能使用C++来开发DAPP，门槛降低了几个数量级，对开发者来说是非常友好了。

由于目前官方尚未发布FIBOS平台币FO的钱包，目前大多是开发者在进场兑换FO。 因而做了一个方便普通用户，可以直接使用EOS来购买FO币及FIBOS平台RAM的。具体的操作见下面
### FO账户名与EOS账户名规则类似 FO公钥地址以FO开头，区别与EOS开头，后面部分规则是一样的

## 第一步  创建FIBOS平台帐号
### 方法1 官方发布了一个免费注册帐号的接口，但有种种限制  [官方接口](https://fibos.io/docs/guide/advanced/createaccount.md.html) 
### 方法2 使用任意钱包，转账 0.1 个以上的EOS（依EOS与FO兑换比例，及内存价格不同可能会有所浮动，扣掉创建账户费用大概2个FO左右，其他剩余的FO在您创建的账户中）到 eos2foeos2fo 这个地址，并将你想要的12位FO账户名和你的公钥地址填入备注信息中即可（FO账户名和你的公钥地址需用减号符 – 隔开）
    备注的例子 fooooooooooo-FO5hY1YDZAcuGNAmhaWUY2EhxpcrA2UQYcwUvbJDPScoaatbdL4r
    注意：fooooooooooo为您想创建的FIBOS平台帐号名，FO5hY1YDZAcuGNAmhaWUY2EhxpcrA2UQYcwUvbJDPScoaatbdL4r为owner和active公钥
        FO的账户名只能由12345abcdefghijklmnopqrstuvwxyz字符组成，目前只可以12位
        FO的公钥以FO开头，可以把EOS账户的公钥的EOS替换为FO来使用，私钥是相同的

## 第二步  EOS兑换FO币
### 方法 使用任意钱包，转账 0.1 个以上的EOS（依EOS与FO兑换比例可能会有所浮动）到 eos2foeos2fo 这个地址，并将你的12位FO账户名填入备注信息中即可
    备注的例子 fooooooooooo
    注意：打入的EOS将全部兑换为FO币，并打入您备注的FO账户中

## 另外 EOS直接购买FIBOS内存RAM
### 方法 使用任意钱包，转账 0.1 个以上的EOS（依EOS与FO兑换比例，及内存价格不同可能会有所浮动）到 eos2foeos2fo 这个地址，并将你的12位FO账户名加buyram填入备注信息中即可 （FO账户名和buyram需用减号符 – 隔开）
    备注的例子 fooooooooooo-buyram
    注意：打入的EOS将全部兑换为FO币，然后会全部购买RAM到您备注的FO账户中
    
    
###欢迎到电报群讨论聊天
[https://t.me/eos2fo](https://t.me/eos2fo)
