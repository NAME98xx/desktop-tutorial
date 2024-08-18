适用于surge的游戏规则 
需要新建策略组 Game全局
从sstap rule搬运

例子策略组需要新建Game全局
然后添加规则集到surge
格式 IP-CIDR,xx.xx.xx.xx/24,Game全局
不按照上面规则填写不会生效
