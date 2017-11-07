# 目录

* [I. Spring Framework概览](I.Overview_of_Spring_Framework/README.md)
    * [1. Spring入门](I.Overview_of_Spring_Framework/1.Getting_Started_with_Spring.md)
    * [2. Spring Framework介绍](I.Overview_of_Spring_Framework/2.Introduction_to_the_Spring_Framework.md)
        * [2.1 依赖注入和控制反转](I.Overview_of_Spring_Framework/2.1.Dependency_Injection_and_Inversion_of_Control.md)
        * [2.2 模块](I.Overview_of_Spring_Framework/2.2.Framework_Modules.md)
            * [2.2.1 核心容器](I.Overview_of_Spring_Framework/2.2.Framework_Modules.md#221-核心容器)
            * [2.2.2 AOP和Instrumentation](I.Overview_of_Spring_Framework/2.2.Framework_Modules.md#222-aop和instrumentation)
            * [2.2.3 消息传递](I.Overview_of_Spring_Framework/2.2.Framework_Modules.md#223-消息传递)
            * [2.2.4 数据访问/集成](I.Overview_of_Spring_Framework/2.2.Framework_Modules.md#224-数据访问集成)
            * [2.2.5 Web](I.Overview_of_Spring_Framework/2.2.Framework_Modules.md#225-web)
            * [2.2.6 测试](I.Overview_of_Spring_Framework/2.2.Framework_Modules.md#226-测试)
        * [2.3 使用场景](I.Overview_of_Spring_Framework/2.3.Usage_scenarios.md)
            * [2.3.1 依赖管理和命名规约](I.Overview_of_Spring_Framework/2.3.1Dependency_Management_and_Naming_Conventions.md)
            * [      Spring的依赖和依赖于Spring](I.Overview_of_Spring_Framework/2.3.1Dependency_Management_and_Naming_Conventions.md#Spring的依赖和依赖于Spring)
            * [2.3.2 日志](I.Overview_of_Spring_Framework/2.3.2Logging.md)
* [II. Spring Framework 4.x版中的新特性](II.What’s_New_in_Spring_Framework_4.x/README.md)
    * [3. New Features and Enhancements in Spring Framework 4.0](https://docs.spring.io/spring/docs/4.3.12.RELEASE/spring-framework-reference/htmlsingle/#new-in-4.0)
        * 3.1. Improved Getting Started Experience
        * 3.2. Removed Deprecated Packages and Methods
        * 3.3. Java 8 (as well as 6 and 7)
        * 3.4. Java EE 6 and 7
        * 3.5. Groovy Bean Definition DSL
        * 3.6. Core Container Improvements
        * 3.7. General Web Improvements
        * 3.8. WebSocket, SockJS, and STOMP Messaging
        * 3.9. Testing Improvements
    * [4. New Features and Enhancements in Spring Framework 4.1](https://docs.spring.io/spring/docs/4.3.12.RELEASE/spring-framework-reference/htmlsingle/#new-in-4.1)
        * 4.1. JMS Improvements
        * 4.2. Caching Improvements
        * 4.3. Web Improvements
        * 4.4. WebSocket Messaging Improvements
        * 4.5. Testing Improvements
    * [5. New Features and Enhancements in Spring Framework 4.2](https://docs.spring.io/spring/docs/4.3.12.RELEASE/spring-framework-reference/htmlsingle/#new-in-4.2)
        * 5.1. Core Container Improvements
        * 5.2. Data Access Improvements
        * 5.3. JMS Improvements
        * 5.4. Web Improvements
        * 5.5. WebSocket Messaging Improvements
        * 5.6. Testing Improvements
    * [6. New Features and Enhancements in Spring Framework 4.3](https://docs.spring.io/spring/docs/4.3.12.RELEASE/spring-framework-reference/htmlsingle/#new-in-4.3)
        * 6.1. Core Container Improvements
        * 6.2. Data Access Improvements
        * 6.3. Caching Improvements
        * 6.4. JMS Improvements
        * 6.5. Web Improvements
        * 6.6. WebSocket Messaging Improvements
        * 6.7. Testing Improvements
        * 6.8. Support for new library and server generations
* [III. 核心技术](III.Core_Technologies/README.md)
    * [7. IoC容器](III.Core_Technologies/7.The_IoC_container.md)
        * [7.1 Spring容器和bean简介](III.Core_Technologies/7.1.Introduction_to_the_Spring_IoC_container_and_beans.md)
        * [7.2 容器概览](III.Core_Technologies/7.2.Container_overview.md)
            * [7.2.1 配置元数据](III.Core_Technologies/7.2.1.Configuration_metadata.md)
            * [7.2.2 实例化容器](III.Core_Technologies/7.2.2.Instantiating_a_container.md)
            * [7.2.3 使用容器](III.Core_Technologies/7.2.3.Using_the_container.md)
        * [7.3 bean概览](III.Core_Technologies/7.3.Bean_overview.md)
            * [7.3.1 bean命名](III.Core_Technologies/7.3.1.Naming_beans.md)
            * [7.3.2 bean初始化](III.Core_Technologies/7.3.2.Instantiating_beans.md)
        * [7.4 依赖](III.Core_Technologies/7.4.Dependencies.md)
            * [7.4.1 依赖注入](III.Core_Technologies/7.4.1.Dependency_Injection.md)
            * [7.4.2 依赖和配置的细节](III.Core_Technologies/7.4.2.Dependencies_and_configuration_in_detail.md)
            * [7.4.3 使用depends-on](III.Core_Technologies/7.4.3.Using_depends-on.md)
            * [7.4.4 延迟初始化的bean](III.Core_Technologies/7.4.4.Lazy-initialized_beans.md)
* [IV. 测试](IV.Testing/README.md)
    * [13. Spring测试介绍](IV.Testing/13.Introduction_to_Spring_Testing.md)
    * [14. 单元测试](IV.Testing/14.Unit_Testing.md)
        * [14.1 Mock对象](IV.Testing/14.1Mock_Objects.md)
        * [14.2 支持单元测试的类](IV.Testing/14.2.Unit_Testing_support_Classes.md)
    * [15. 集成测试](IV.Testing/15.Integration_Testing.md)
        * [15.1 概览](IV.Testing/15.1.Overview.md)
        * [15.2 集成测试的目标](IV.Testing/15.2.Goals_of_Integration_Testing.md)
            * [15.2.1 上下文管理及缓存](IV.Testing/15.2.Goals_of_Integration_Testing.md#1521-上下文管理及缓存)
            * [15.2.2 测试固件的依赖注入](IV.Testing/15.2.Goals_of_Integration_Testing.md#1522-测试固件的依赖注入)
            * [15.2.3 事务管理](IV.Testing/15.2.Goals_of_Integration_Testing.md#1523-事务管理)
            * [15.2.4 支持集成测试的类](IV.Testing/15.2.Goals_of_Integration_Testing.md#1524-支持集成测试的类)
        * [15.3 JDBC测试支持](IV.Testing/15.3.JDBC_Testing_Support.md)
        * [15.4 注解](IV.Testing/15.4.Annotations.md)
* [V. 数据访问](V.Data_Access/README.md)
    * [17. 事务管理](V.Data_Access/17.Transaction_Management.md)
        * [17.1 Spring Framework事务管理介绍](V.Data_Access/17.1.Introduction_to_Spring_Framework_transaction_management.md)
        * [17.2 Spring Framework的事务支持模型的优点](V.Data_Access/17.2.Advantages_of_the_Spring_Framework's_transaction_support_model.md)
            * [17.2.1 全局事务](V.Data_Access/17.2.Advantages_of_the_Spring_Framework's_transaction_support_model.md/#1721-全局事务)
            * [17.2.2 本地事务](V.Data_Access/17.2.Advantages_of_the_Spring_Framework's_transaction_support_model.md/1722-本地事务)
            * [17.2.3 Spring Framework的一致性编程模型](V.Data_Access/17.2.Advantages_of_the_Spring_Framework's_transaction_support_model.md/#1723-Spring-Framework的一致性编程模型)
* [VI. Web](VI.The_Web/README.md)
    * [22. Web MVC框架](VI.The_Web/22.Web_MVC_framework.md)
        * [22.1 Spring Web MVC框架介绍](VI.The_Web/22.1.Introduction_to_Spring_Web_MVC_framework.md)
            * [22.1.1 Spring Web MVC的特性](VI.The_Web/22.1.1.Features_of_Spring_Web_MVC.md)
            * [22.1.2 其他MVC实现的可插拔性](VI.The_Web/22.1.2.Pluggability_of_other_MVC_implementations.md)
        * [22.2 DispatcherServlet](VI.The_Web/22.2.The_DispatcherServlet.md)
            * [22.2.1 WebApplicationContext中的特殊Bean类型](VI.The_Web/22.2.1.Special_Bean_Types_In_the_WebApplicationContext.md)
            * [22.2.2 默认DispatcherServlet配置](VI.The_Web/22.2.2.Default_DispatcherServlet_Configuration.md)
