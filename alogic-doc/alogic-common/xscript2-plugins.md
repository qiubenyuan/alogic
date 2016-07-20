xscript2.0插件参考
=================

xscript提供了灵活的插件机制，并提供了相应的内置插件，并鼓励开发者面向专业领域开发插件。

已知的插件集合包括：

- 内置插件集合
    - 使用插件
        - [使用插件using](xscript-plugins/using.md)
    - 上下文变量
        - [检查变量check](xscript-plugins/check.md)
        - [检查变量并设置缺省值checkAndSet](xscript-plugins/checkAndSet.md)
        - [设置一个常量constants](xscript-plugins/constants.md)
        - [设置当前时间now](xscript-plugins/now.md)
        - [设置一个随机字符标示uuid](xscript-plugins/uuid.md)
        - [设置一个变量set](xscript-plugins/set.md)
        - [设置一个通过公式计算的变量formula](xscript-plugins/formula.md)
    - 文档操作
        - [获取一个变量值，并输出到文档set](xscript-plugins/get.md)
        - [将一个预定义的JSON文档输出到文档template](xscript-plugins/template.md)
        - [通过定位切换文档的当前节点location](xscript-plugins/location.md)
    - 日志
        - [日志输出log](xscript-plugins/log.md)
        - [定义日志处理器logger](xscript-plugins/logger.md)
    - 工具
        - [加密encrypt](xscript-plugins/encrypt.md)
        - [解密descrypt](xscript-plugins/descrypt.md)
    - 多线程
        - [异步async](xscript-plugins/async.md)
        - [睡眠sleep](xscript-plugins/sleep.md)
    - 控制语句
        - [条件switch](xscript-plugins/switch.md)
        - [循环repeat](xscript-plugins/repeat.md)
        - [定义异常处理器except](xscript-plugins/except.md)
        - [定义最终处理器finally](xscript-plugins/finally.md)
        - [抛出异常throw](xscript-plugins/throw.md)
        - [包含脚本文件include](xscript-plugins/include.md)
- idu插件集合
    - [命名空间idu](xscript-plugins-idu/idu.md)
    - 数据库操作
	    - [创建数据库连接db](xscript-plugins-idu/db.md)
	    - [指定id是否可用idExist](xscript-plugins-idu/idExist.md)
	    - [查询列表list](xscript-plugins-idu/list.md)
	    - [查询个体对象query](xscript-plugins-idu/query.md)
	    - [新增语句new](xscript-plugins-idu/new.md)
	    - [删除语句delete](xscript-plugins-idu/delete.md)
	    - [更新语句update](xscript-plugins-idu/update.md)
    - 缓存操作
	    - [创建缓存连接](xscript-plugins-idu/cache.md)
	    - [获取缓存对象(load)](xscript-plugins-idu/load.md)
	    - [过期指定缓存对象(expire)](xscript-plugins-idu/expire.md)
- rest插件集合


