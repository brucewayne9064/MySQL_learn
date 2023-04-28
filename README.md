# MySQL_learn

使用方法：

先下载两个文件：`create.sql`, `populate.sql`

登录mysql，然后创建一个database：

```sql
create database crashcourse;
```

选取该database：

```sql
use crashcourse;
```

执行create.sql脚本:

```sql
source ~/Desktop/mysql_scripts/create.sql;
```

执行populate.sql脚本:

```sql
source ~/Desktop/mysql_scripts/populate.sql;
```

查看是否成功：

```sql
show tables;
```
