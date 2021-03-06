# 别名



别名指向特定的函数版本，可通过别名来调用该版本的函数，您可使用别名服务各种环境请求，将触发器绑定别名上，发布新版本或回滚时，只需将别名指向对应的函数版本，无需修改触发器，即可完成函数迭代。

## 创建别名

1.用户登陆函数服务，进入“函数列表“页面。

2.在“函数列表“中选择要配置的函数，单击函数名称进入该函数详情页。

3.在函数详情页，选择函数版本，单击“操作”—“创建别名”，弹出“创建别名”窗口。

4.在“创建别名”界面，输入要创建的函数别名的配置信息见表1，* 为必填项。

5.单击“确定”，完成别名创建。

表1 函数别名配置信息表

| 配置信息  | 说明                                                         |
| --------- | ------------------------------------------------------------ |
| * 别名名称 | 只能包含字母，数字、下划线和中划线；以字母/数字开头、结尾；长度不超过16个字符 |
| * 对应版本 |  从已有函数版本中关联函数版本                                 |
|  描述      | 最大支持1000个英文字母、数字、空格、逗号、英文句号、中文。   |


**说明：**

别名名称创建后不可修改。

单个函数下最多可以创建10个别名。
 

## 删除别名

函数详情页面，选择函数别名，单击“操作”—“删除别名”，弹出“删除提示”，确认无误后单击“确定”，删除函数别名。

删除别名只会删除别名本身，不会删除别名指向的函数版本，删除别名前需先移除绑定在该别名上的触发器。
