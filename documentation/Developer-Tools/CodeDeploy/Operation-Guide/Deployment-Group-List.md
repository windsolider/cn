## 应用部署组列表

在应用详情页，有两个分页，分别展示了应用中的部署组、里程碑。

![Alt text](https://github.com/jdcloudcom/cn/blob/edit/image/CodeDeploy/Ch/Oper-3%EF%BC%88Ch%EF%BC%89.png)


在部署组分页中，列出此应用下所有的部署组，并可支持“新建部署组”。

指定部署组，可支持以下操作：

- 发起部署：指定部署组，进行部署。详见“操作指南-发起部署”
- 部署历史：将跳转到“部署历史”页，展示此应用下指定部署组的部署历史
- 编辑：可对除部署组名称、部署类型外的部署组信息进行编辑
- 删除：删除此部署组。请注意，删除部署组不会触发对部署组内的部署目标（云主机）的任何操作，也不会对部署组内的部署目标（云主机）所在的负载均衡虚拟服务器组做任何操作，即这些云主机依旧会属于由云部署所创建的虚拟服务器组中。为避免资源浪费，在删除部署组后，请至负载均衡，删除关联的虚拟服务器组

在里程碑分页中，详见“操作指南-应用里程碑列表”。
