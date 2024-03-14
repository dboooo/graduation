# 管理系统后端文件介绍

## sql文件夹

负责生成生成sql文件，建立好数据库。

## src文件夹

main文件夹：主要的功能实现

    |- main
        - java
            - common：公用方法/接口，很多地方都会用到的方法
            - config：配置文件
            - controller：控制的接口，更多的是上层接口
            - converter: 转换器，转换不同类型
            - filter：做校验，验证的
            - mapper： 后端路由
            - model：数据控制，数据定义
            - entity：也是数据控制
            - form：数据表单
            - query：不同的查询
            - plugin：java项目的一些插件
            - security：安全
            - service：拦截请求并相应
        - resources
        

test文件夹：负责测试功能
