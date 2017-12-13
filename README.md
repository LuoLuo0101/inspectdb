# inspectdb
Django ORM 数据库表反向生成 Django ORM inspectdb

### 项目介绍
1. 本项目是为了测试 Django ORM 反向解析数据库中的表而建立的

2. 注意Django2.0 会和 pymysql 冲突，需要改 django.db.backends.mysql.base.py 中的代码

3. 将那个文件中的代码的35-36行注释掉