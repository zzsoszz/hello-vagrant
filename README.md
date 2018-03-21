# hello-vagrant
1.添加box
vagrant box add base your_box_addres

2.初始化
vagrant init
vagrant init box_name
如果你添加的box名称不是[base]，那么需要在初始化的时候指定名称

3.启动虚拟机
vagrant up


vagrant up （启动虚拟机）  
vagrant halt （关闭虚拟机——对应就是关机）  
vagrant suspend （暂停虚拟机——只是暂停，虚拟机内存等信息将以状态文件的方式保存在本地，可以执行恢复操作后继续使用）  
vagrant resume （恢复虚拟机—— 与前面的暂停相对应）  
vagrant destroy （删除虚拟机，删除后在当前虚拟机所做进行的除开Vagrantfile中的配置都不会保留）  



vagrant ssh