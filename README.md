# php-interview-demo

## PHP 技能实测项目要求：

1. 非常熟悉 PHP 语言，三年以上 PHP 开发经验；
1. 非常熟悉 MYSQL 数据库及 SQL 语句；
1. 熟悉 MVC 设计模式；
1. 熟悉 Composer 包管理工具；
1. 熟悉 Codeception 测试框架；
1. 熟悉 Linux 常用操作命令；
1. 了解 HTML5、HTML、CSS、XML、JavaScript 等相关语言；
1. 使用过 Yii2 框架者优先；
1. 代码风格符合此编码规范者优先 https://github.com/yiisoft/yii2/blob/master/docs/internals/core-code-style.md

## 用户地址模块开发说明

1. 模块可使用 Composer 安装。
1. 用户地址管理相关接口：
    - 城市列表
    - 新增地址（字段有姓名、手机（`/^09\d{8}$/`）、城市、县区、地址、邮编等）
    - 地址列表
    - 查看地址详情
    - 修改地址详情
    - 删除地址
1. 基于 Codeception 编写接口测试。
1. 基于以下目录结构进行开发：
    ```
    yii2-tsmd-address/
        config/
        src/
            api/
            components/
            helpers/
                TwCityHelper.php
            migrations/
            models/
            tests/
                api/
                unit/
    ```
1. 根据以上要求确定开发思路、评估开发时长。