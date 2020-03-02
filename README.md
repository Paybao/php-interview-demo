# php-interview-demo

## PHP 技能实测项目要求：

1. 非常熟悉 PHP 开发语言，三年以上 PHP 开发经验；
1. 非常熟悉 Yii2 框架，一年以上 Yii2 开发经验；
1. 熟悉 Codeception 测试框架；
1. 熟悉 MYSQL 数据库及 SQL 语句；
1. 熟悉 HTML5、HTML、CSS、XML、JavaScript 等相关语言，有一定的前端编程能力；
1. 熟悉 Linux 常用操作命令；
1. 熟悉 DynamoDB 者优先；
1. 遵循「高內聚，低耦合」的设计思路者优先；
1. 代码风格符合此编码规范者优先 https://github.com/yiisoft/yii2/blob/master/docs/internals/core-code-style.md

## Yii2 用户地址模块开发说明

1. 模块可应用于 Yii2 框架。
1. 开发以下地址管理相关接口：
    - 城市列表
    - 提取，从字符串中提取城市、县区、地址等
    - 创建，字段有姓名、手机（`/^09\d{8}$/`）、城市、县区、地址、邮编等
    - 搜索
    - 查看
    - 修改
    - 删除
1. 基于 Codeception 编写接口测试。
1. 基于以下目录结构进行开发。
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
1. 根据以上要求先确定整体开发思路以及开发时长。