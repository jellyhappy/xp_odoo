# 币种设置

odoo支持多币种，用户需要勾选多币种用户组才可以设置币种。币种设置菜单：会计-配置-会计-货币：

![](images/13.png)

## 精度设置

我们在销售单、采购单中通常可以看到小计的精度是2位，这是因为通常默认的货币单位的精度是2位。如果想要更精确的小数位数，就需要更改货币单位中的精度设置：

![](images/14.png)

这里有个问题需要说明一下，看起来好像精度可以无限设置，但实际上当你的小数精度设置到7位时，就会发现系统提示你，设置的精度必须大于0。也就是说，实际上货币精度的可设置的范围为0-6位小数。

![](images/15.png)
