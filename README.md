# MySQLva
可执行jar包已整合JDBC驱动，在装有java和mysql的环境中可直接运行。
## 使用说明：
* 主页面使用说明：
    * 通过 双击表名 来打开相应数据管理标签页
    * 通过 菜单栏：新建 来建库和建表
    * 通过 菜单栏：执行 来执行多条或单条复杂的sql语句
    * 通过 菜单栏：设置 来修改表格中空值的表示（1）和重置页面和设置（2）
    * 通过 下方显示区域 查看操作的详细信息
* 数据管理标签页使用说明：
    * 通过  增加按键 来增加弹出窗口表格中被选中的数据
    * 通过  删除按键 来删除数据表格中被选中（可多选）的数据
    * 通过  双击表格 来修改数据，退出编辑状态时，向数据库提交修改的值
    * 通过  查找按键 来查找一行表格（3）中的约束数据，单元格空白则这一列没有约束

#### 注释：
（1）:heavy_exclamation_mark::heavy_exclamation_mark::heavy_exclamation_mark:
    表格中空值用特定字符串表示，和空白字符串做以区分。
    以特定字符串表示方便从表格分辨或输入空值。
    "Null(1)"字符串默认被用作表示空值，大小写敏感，可从设置修改。这种表示只用在表格中。

（2） 
    重置页面和设置，程序回到初始状态。

（3）
    一行表格 指数据显示表格下面，按钮上面，被选中时为青色的那一行表格。

注意：刷新按键用于重新向数据库查询数据，仅当在本程序外修改或通过 菜单栏：执行 执行sql语句时候需要手动刷新。

  ![](https://github.com/TuJiaoJiao/MySQLva/blob/master/image/2.png)  
