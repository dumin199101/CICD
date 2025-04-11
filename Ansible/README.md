# Ansible
> Ansible相关知识点 
> 
> 参考文档:
>> [持续集成与交付技术1-Git工具使用（jenkins、gitlab）](https://blog.csdn.net/weixin_41191813/article/details/114690877)
> 
>> [持续集成与交付技术2-jenkins使用结合ansible与k8s集群](https://blog.csdn.net/weixin_41191813/article/details/114965601) 
> 
> Ansible是一种自动化配置管理工具
> 1. 远程系统配置：可以在大量服务器上自动执行配置任务。
> 2. 部署应用：方便地部署软件和应用程序。
> 3. 一致性管理：确保系统配置的一致性和准确性。
>
> Jenkins 则是一个持续集成服务器，用于：
> 1. 持续集成：自动构建、测试和集成代码。
> 2. 构建自动化：监控代码变更并触发构建过程。
> 3. 提供可视化界面：便于监控和管理构建过程。
> 
> 它们的主要区别在于：
> 1. 重点不同：Ansible 侧重于系统配置和部署，Jenkins 关注软件开发的持续集成。
> 2. 使用场景：Ansible 适用于大规模系统管理，Jenkins 主要在软件开发流程中使用。
> 3. 复杂性：Ansible 相对简单易用，Jenkins 提供更丰富的功能和插件。
> 
> 在实际使用中，两者可以结合使用：
> 1. Ansible 可以用于部署Jenkins服务器。
> 2. Jenkins 的构建过程可以包含 Ansible任务，实现更复杂的部署流程。

## Ansible安装

```shell
yum install ansible -y
```

