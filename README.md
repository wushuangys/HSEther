# HSEther ether wallet create 
基于此静态库的项目ZAG已经顺利上线

iOS商店： https://itunes.apple.com/cn/app/qq/id1354866033?mt=8

ZAG官网： http://zagcoin.org/

融资报道： https://www.baidu.com/s?wd=zag%E9%92%B1%E5%8C%85&rsv_spt=1&rsv_iqid=0xd2b7448d00029c68&issp=1&f=8&rsv_bp=0&rsv_idx=2&ie=utf-8&tn=baiduhome_pg&rsv_enter=1&rsv_sug3=11&rsv_sug1=14&rsv_sug7=100&rsv_t=5121XDphVh%2FemYDjnPZ74X93QgwvtkwJ%2FDQgBbS8BdiVSykHQq7Xobc6yr1TiyP1Kgir&rsv_sug2=0&inputT=4721&rsv_sug4=4721

技术支持公司：重庆迪斯马森科技有限公司 http://www.dismason.com/

## 您的star是我最大的动力

### 1.0 临时主要功能（2018-04-20）：

1 离线创建钱包 生成对应算法助记词、私钥、keystore（生成钱包

2 验证钱包keystore和密码 （keystore导入钱包

3 验证私钥（私钥导入钱包

4 验证助记词（助记词导入钱包

以上安全起见，不调用接口实现，全部本地离线验证。


### 1.2 主要添加功能（预计2018-04-30）：

1 查询以太坊余额

2 查询基于以太坊公链token代币余额

3 查询交易记录

4 查询交易详情

------------------------------------------------
# 支持 cocoaPods

cocoaPods HSEther

ios version 10.0+

------------------------------------------------
# 具体用法 详见Demo
创建钱包

+(void)hs_createWithPwd:(NSString *)pwd block:(void(^)()block;
                  
 助记词导入
 
+(void)hs_inportMnemonics:(NSString *)mnemonics pwd:(NSString *)pwd block:(void(^)()block;

 KeyStore 导入
 
+(void)hs_importKeyStore:(NSString *)keyStore pwd:(NSString *)pwd block:(void(^)()block;

私钥导入

+(void)hs_importWalletForPrivateKey:(NSString *)privateKey pwd:(NSString *)pwd block:(void(^)()block;
                              
                              

------------------------------------------------
## 提供 非静态库源码，包括iOS和Android
## 提供 技术支持，包括iOS和Android
## 联系wechat： iHoushuai
------------------------------------------------
                              
                  
