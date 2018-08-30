

# 恢复运行 小额我们会垫付先在FIBOS网执行，一般会在半分钟之内，大额的需要等官方到帐时间，一般为1分钟半

另执行完后可以在这个区块链网站查询了[http://explorer.fibos.rocks/](http://explorer.fibos.rocks/)


# EOS2FO 用EOS钱包直接购买FO

首先庆祝FIBOS上线，可以直接使用JavaScript来做开发，相比EOS目前只能使用C++来开发DAPP，门槛降低了几个数量级，对开发者来说是非常友好了。

由于目前官方尚未发布FIBOS平台币FO的钱包，目前大多是开发者在进场兑换FO。 因而做了一个方便普通用户，可以直接使用EOS来购买FO币及FIBOS平台RAM的。具体的操作见下面，测试阶段请不要大额转

### 有一定基础的可以直接看着
    1. 创建:FO帐号名字加空格(或-)加公钥作为备注发送0.01个EOS到eos2foeos2fo这个EOS帐号，创建帐号大概花费0.003个EOS，剩eos自动买成FO
    2. 买FO币：FO帐号名字作为备注发送EOS到eos2foeos2fo这个EOS帐号，所有eos自动买成FO到备注的FO帐号
    3. 买RAM:FO帐号名字加空格加buyram作为备注发送EOS到eos2foeos2fo这个EOS帐号，所有eos自动买成FO到备注的FO帐号
       创建帐号备注样式：fooooooooooo-FO5hY1YDZAcuGNAmhaWUY2EhxpcrA2UQYcwUvbJDPScoaatbdL4r
       买FO币备注样式：fooooooooooo
       买RAM备注样式：fooooooooooo-buyram 

### FO账户名与EOS账户名规则类似 FO公钥地址以FO开头，区别与EOS开头，后面部分规则是一样的

## 第一步  创建FIBOS平台帐号
### 方法1 官方发布了一个免费注册帐号的接口，但有种种限制，可以查询账户是否存在没有限制  [官方接口](https://fibos.io/docs/guide/advanced/createaccount.md.html) 
### 方法2 使用任意钱包，转账 0.01 个以上的EOS（依EOS与FO兑换比例，及内存价格不同可能会有所浮动，扣掉创建账户费用大概2个FO左右，其他剩余的FO存在您创建的账户中）到 eos2foeos2fo 这个地址，并将你想要的12位FO账户名和你的公钥地址填入备注信息中即可（FO账户名和你的公钥地址需用减号符 – 隔开）
    备注的例子 fooooooooooo-FO5hY1YDZAcuGNAmhaWUY2EhxpcrA2UQYcwUvbJDPScoaatbdL4r
    注意：fooooooooooo为您想创建的FIBOS平台帐号名，FO5hY1YDZAcuGNAmhaWUY2EhxpcrA2UQYcwUvbJDPScoaatbdL4r为owner和active公钥
        FO的账户名只能由12345abcdefghijklmnopqrstuvwxyz字符组成，目前只可以12位
        FO的公钥以FO开头，可以把EOS账户的公钥的EOS替换为FO来使用，私钥是相同的
        请确定账户名没被别人使用，再进行创建，否则会创建失败,EOS无法自动退款
        

## 第二步  EOS兑换FO币
### 方法 使用任意钱包，转账 0.01 个以上的EOS（依EOS与FO兑换比例可能会有所浮动）到 eos2foeos2fo 这个地址，并将你的12位FO账户名填入备注信息中即可
    备注的例子 fooooooooooo
    注意：打入的EOS将全部兑换为FO币，并打入您备注的FO账户中,确保备注的FO账户是您的账户

## 另外 EOS直接购买FIBOS内存RAM
### 方法 使用任意钱包，转账 0.01 个以上的EOS（依EOS与FO兑换比例，及内存价格不同可能会有所浮动）到 eos2foeos2fo 这个地址，并将你的12位FO账户名加buyram填入备注信息中即可 （FO账户名和buyram需用减号符 – 隔开）
    备注的例子 fooooooooooo-buyram
    注意：打入的EOS将全部兑换为FO币，然后会全部购买RAM到您备注的FO账户中,确保备注的FO账户是您的账户
 
### 说明
    从转账到购买FO成功需要1分钟左右,目前FO网络还在初期，请尽量不要大额购买
    FO兑换为EOS需要您自己操作，因为FO账户控制权是在您自己手中的
    如果帐号和公钥格式不正确，或者转账金额小于0.01EOS，转账不会成功，多数钱包只会提示内存cpu资源不足，请注意检查
    如有其他问题可加微信biteyebot进群

### 查看链上成功记录   [https://eosflare.io/account/eos2foeos2fo](https://eosflare.io/account/eos2foeos2fo) 
    
### 欢迎到电报群讨论聊天   [https://t.me/eos2fo](https://t.me/eos2fo)
