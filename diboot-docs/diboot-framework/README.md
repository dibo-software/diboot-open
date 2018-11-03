# diboot-framework介绍

**diboot-framework**是一个广泛适用于Java Web开发的轻量级封装框架，基于**Spring**+**Mybatis**，
提供开发过程中常用场景的轻量化实现，主要有:
1. CRUD通用封装：
    > 支持增删改查、批量插入、更新指定字段、动态查询条件等
2. MVC通用封装：
    > 提供Model静态类F以及Controller、RestController相关的常用CRUD封装
3. 认证与安全：
    > 提供基于Shiro的JWT授权认证 以及 XSS、CSRF等安全问题防护的实现
4. 系统参数配置：
    > 支持兼容数据库表或Properties文件存放的系统参数配置实现方案
5. 系统日志记录：
    > 提供系统异常日志、操作日志、跟踪日志的数据库记录实现
6. 常用工具类：
    > 如日期类D、字符串类S、校验类V、Bean工具类、Json工具类、加解密类、Long型id生成器类等
7. 常用基础模型：
    > 提供Web开发常用的用户、角色、菜单、权限、文件、元数据等基础功能的支持
-------
**[diboot-framework](https://github.com/dibo-software/diboot)是diboot家族的基础框架，轻量级高性能是我们追求的目标，
目前的封装是基于我们团队近几年的开发经历打磨而来，如果您有任何优化建议欢迎随时贡献idea或代码。**