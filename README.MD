### zfun

  > A function and class sets in common use.

### Install:

    pip3 install -U zfun

### List:
  - Class

  - Function


### Log

  - Version 1.1.4
  
    Modify `MYSQL.ExecQuery`. 修改数据库查询返回值，`res[0]`为列名。不兼容以前的版本。

    Add Class `BIO`. 增加生物信息学常用内容。增加静态方法`BIO.humanChrName`，返回人类染色体名称的字典。

  - Version 1.1.0

  精简了常用函数：nowf(), mkdirf(),MYSQL(), mkscript()