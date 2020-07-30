[返回首页](https://opisthebest.github.io/OP-is-the-best/)            

旁路由模式下如果出现访问国内网路缓慢、不通，请尝试在如下图中位置添加规则：          
iptables -t nat -I POSTROUTING -j MASQUERADE                 
![aPbDkn.png](https://s1.ax1x.com/2020/07/27/aPbDkn.png)                    
