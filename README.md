## CMDB 录入规范
- 资产编号
    - 资产编号是唯一必须存在字段，资产编号不存在的资产一律不入库
- 型号要求
    - 规范的型号应为：`品牌+系列（如果有）+型号`，中间使用 **一个空格** 隔开
        - 如：`联想 ThinkPad X230`
        - 如：`苹果 iMac`
    - 统一在型号中加上品牌
        - 如: 方正的`F191W`机器，正确格式应为`方正 F191W`
    - 型号中字母大小写需要按官方写法
        - 如: `ThinkPad` 不应该写成 `Thinkpad`、`thinkpad`、`think pad`等
    - 品牌优先使用中文
        - 如：使用`联想`作为品牌名字，不使用`Lenovo`；
        - 如：使用`苹果`而不使用`Apple`;
        - 如：`IBM`通常不叫中文名，所以直接使用`IBM`作为其品牌名称
    - 组装台式机 的设备型号字段留空
- 使用人
    - 需要完全对应使用人的名字，不要出现：`张三使用`，`张三部门使用`等
- 设备类型
    - PC
        - 目前PC类型只有: `主机`、`显示器`、`一体机`、`笔记本`，需要加类型前请考虑一下是否和原有类型重复  
            如： `苹果一体机` ，是属于`一体机`类型，`苹果`只是品牌
