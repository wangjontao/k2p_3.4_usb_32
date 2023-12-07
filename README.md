小白自编译步骤
1、从已经有的workflow里复制一个模版
![1](https://github.com/fightroad/Padavan-KVR/assets/39027157/611c13d7-0b32-4eb1-80d8-6bebaaf6913c)

2、新建一个action脚本
![2](https://github.com/fightroad/Padavan-KVR/assets/39027157/42120ab1-e245-4f04-a984-27f381e82565)
![3](https://github.com/fightroad/Padavan-KVR/assets/39027157/75cefd7d-fe60-40c8-87b1-1c250c98e425)
![4](https://github.com/fightroad/Padavan-KVR/assets/39027157/a5c28213-3bbb-4ad5-872e-a3639acb6496)

3、自定义自己的脚本
![配置1](https://github.com/fightroad/Padavan-KVR/assets/39027157/4bc31b0d-a1c8-4ed9-8ff7-f6babb060ba5)
![配置2](https://github.com/fightroad/Padavan-KVR/assets/39027157/617d506c-3cf5-4e03-a5a9-da810ddd4240)

4、开始编译，获取编译后的固件
![5](https://github.com/fightroad/Padavan-KVR/assets/39027157/15c6aed1-41b9-41e2-b13b-a5fd6063cbd6)
![6](https://github.com/fightroad/Padavan-KVR/assets/39027157/9ab4089e-0eab-4728-8cdf-3960e503f640)


# Padavan
基于hanwckf,chongshengB以及padavanonly的源码整合而来，支持7603/7615/7915的kvr  
编译方法同其他Padavan源码，主要特点如下：  
1.采用padavanonly源码的5.0.4.0无线驱动，支持kvr  
2.添加了chongshengB源码的所有插件  
3.其他部分等同于hanwckf的源码，有少量优化来自immortalwrt的padavan源码  
4.添加了MSG1500的7615版本config  
  
以下附上他们四位的源码地址供参考  
https://github.com/hanwckf/rt-n56u  
https://github.com/chongshengB/rt-n56u  
https://github.com/padavanonly/rt-n56u  
https://github.com/immortalwrt/padavan
  
最后编译出的固件对7612无线的支持已知是有问题的，包含7612的机型比如B70是无法正常工作的  
已测试的机型为MSG1500-7615，JCG-Q20，CR660x  
  
固件默认wifi名称
 - 2.4G：机器名_mac地址最后四位，如K2P_9981
 - 5G：机器名_5G_mac地址最后四位，如K2P_5G_9981

wifi密码
 - 1234567890

管理地址
 - 192.168.2.1

管理账号密码
 - admin
 - admin

**最近的更新代码都来自于hanwckf和MelsReallyBa大佬的4.4内核代码**
- https://github.com/hanwckf/padavan-4.4
- https://github.com/MeIsReallyBa/padavan-4.4
