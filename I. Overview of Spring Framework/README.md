#Part I. Spring框架概览

Spring框架是一个轻量级的解决方案，是*一站式*构建企业级应用的一种选择。同时，Spring是模块化的，你可以仅仅使用你需要的部分。你可以仅使用IoC容器，在上层使用任意web框架；你也可以只使用Hibernate集成代码或者JDBC抽象层。Spring框架支持声明式的事务管理，支持通过RMI或Web服务远程访问你的逻辑，支持以多种方式持久化数据，它提供了一个功能全面的MVC框架，还能让你在不察觉的情况下将AOP功能集成到软件中。

Spring被设计成非侵入式的，这意味着你的领域逻辑代码通常不依赖于框架本身。在集成层（比如数据访问层）会存在对数据访问技术的依赖和Spring的库。但是，使你代码库的其余部分与这些依赖隔离应该是非常容易的。

这份文档是Spring框架特性的参考指南。If you have any requests, comments, or questions on this document, please post them on the [user mailing list](https://groups.google.com/forum/#!forum/spring-framework-contrib). Questions on the Framework itself should be asked on StackOverflow (see https://spring.io/questions).

