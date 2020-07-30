[返回首页](https://opisthebest.github.io/OP-is-the-best/)             

# web页面上传固件升级到新版本/切换到其他版本/回滚              
///你下载的新版本固件，OpenWRT（官方、Lean、Lienol...）一般可以互刷，只要引导方式（BIOS/EFI）是一样的               
///也不存在版本高低说法，可以刷老版本来回滚                    
///这里用的旧luci作为演示。新luci升级差不多，是否保留配置的按钮是在上传好新固件后再出现的                          

* 警告：挂载外接硬盘使用的，请先拔出接口，再升级固件，否则你可能会哭成憨憨！！！                         

* 第一步：                  
![](https://pic.downk.cc/item/5f02aff914195aa594d77020.png)                  
👆系统>备份/升级          

* 第二步：               
![](https://pic.downk.cc/item/5f02b07914195aa594d7af6a.png)                   
👆配置（强烈建议取消勾选，不保留配置避免bug）>选择文件>刷写固件         
///如果升级提示不兼容，建议解压成IMG格式，再上传升级试试                     

* 第三步：   
![](https://pic.downk.cc/item/5f02b20414195aa594d86ca2.png)                         
👆点击处理               

* 第四步：                 
![](https://pic.downk.cc/item/5f02b24c14195aa594d88e61.png)                 
👆等完成(网口灯重新闪烁)                       


# web页面重置固件（仍然是：系统>备份/升级）      

* 第一步：                 
![](https://pic.downk.cc/item/5f02b31e14195aa594d8f4ea.png)                     
👆如图所示点两下（没有这个重置按钮说明你的固件格式不支持重置）     

* 第二步：            
![](https://pic.downk.cc/item/5f02b39714195aa594d933cf.png)             
👆👆等完成(网口灯重新闪烁) (手动安装的插件都会消失)         




