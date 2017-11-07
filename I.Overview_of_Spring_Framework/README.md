# Part I. Spring Framework概览

Spring Framework是一个轻量级的解决方案，是*一站式*构建企业级应用的一种选择。同时，Spring是模块化的，您可以仅仅使用需要的部分。您可以仅使用IoC容器，在上层使用任意web框架；您也可以只使用[Hibernate集成代码](../V.Data_Access/20.3.Hibernate.md)或者[JDBC抽象层](../V.Data_Access/19.1.Introduction_to_Spring_Framework_JDBC.md)。Spring Framework支持声明式的事务管理，支持通过RMI或Web服务远程访问您的逻辑，支持以多种方式持久化数据，它提供了一个功能全面的[MVC框架](../VI.The_Web/22.1.Introduction_to_Spring_Web_MVC_framework.md)，还能在您未察觉的情况下将[AOP](../III.Core_Technologies/11.1.Introduction.md)功能集成到软件中。

Spring被设计成非侵入式的，这意味着您的领域逻辑代码通常不依赖于框架本身。在集成层（比如数据访问层）会存在对数据访问技术的依赖和Spring的库。但是，使您代码库的其他部分与这些依赖隔离应该是非常容易的。

这份文档是关于Spring Framework功能的参考指南。如果您对本文档有任何要求、意见或疑问，请发送到[用户邮件列表](https://groups.google.com/forum/#!forum/spring-framework-contrib)。关于框架本身的问题，应当在StackOverflow 上进行求教（参阅https://spring.io/questions）。

