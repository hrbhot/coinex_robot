目前只提供二进制程序，秉承开源精神，会在挖矿活动结束后时间以后上传源码。

凡是为eosforce jiqix节点投票的，截图为证，微信后台发给我，我就会回发解压密码。

目前提供了windows/linux的64位版本，以及mac的32/64版本。解压后请注意核对md5校验码，防止被篡改。


自我介绍

	大家好！我是微信公众号 “呆萌小机器人”和“投资呆萌小机器人”的作者，  
    也是eosforce节点jiqix的维护者，也是这个机器人的作者。  
    这次因为时间紧张，来不及挂到微信后台，以后类似的工具我会直接通过微
	信提供，所以希望您能关注本公众号，谢谢关注我的公众号！  
	如果您在EOS创世名单中，请访问eosforce.io下载钱包，灌入私钥，即可领取
	EOSForce链上的EOS。eosforce投票有分红，这是您投票的最大原因和动力！
	如果担心安全隐患，可以在EOS主网上新建帐号，把账户余额转给信号，再领
	取EosForce。  
	jiqix目前为投票者分红95%，所以必须为jiqix投票，谢谢支持！  
	如果有其他疑问，请在github或者微信后台和我联系。  
	
安全申明  

	本人保证github上发布的版本没有恶意代码。但是为了安全起见，请用虚拟机，
	或者完全不带敏感信息的电脑运行此程序。如果出现任何安全事件，本程序概
	不负责。  
	另:可以考虑买丐版云服务器运行本程序，在腾讯官方价格基础上，联系微信号
	wshinewmm还有进一步优惠。  
	
使用说明  

    不带参数运行可以看到帮助，我现在测试使用的参数如下，策略不同、品种不同的话需要调整。  
    如果纯粹以刷量为目的，volin,volout调小，discount调大。  
    如果试图主动赢利，把volin,volout调大，discount调小。  
    
robot -id xxxxxxxxxxxxxxx \
   -key xxxxxxxxxxxxxxxx \
   -discount 0.01 \
   -lsym ETH \
   -rsym USDT \
   -unit 0.01 \
   -volignore 0.005\
   -volin 0.1 \
   -volout 0.3  
   
归档  

    目前只上传程序在此，代码待挖矿结束后提供。  
    https://github.com/gpmn/coinex_robot  
