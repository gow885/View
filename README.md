# View
# 数据库表结构说明

以下是 w_about 表的字段结构图：

```mermaid
flowchart TD
    Center(("w_about 政府信息表"))
    Center ---|Id int(11) 主键自增| F1
    Center ---|name varchar(50) 名称| F2
    Center ---|intro varchar(255) 简介| F3
    Center ---|about_type int(1) 类型| F4
    Center ---|company_name varchar(255) 公司名称| F5
    Center ---|img varchar(255) 图片| F6
    Center ---|plan varchar(50) 行业解决方案经验| F7
    Center ---|patent varchar(50) 产品外观及技术专利| F8
    Center ---|case varchar(50) 长期战略合作伙伴| F9
    Center ---|create_time Datetime 创建时间| F10
    Center ---|update_time Datetime 更新时间| F11
    F1[" "]
    F2[" "]
    F3[" "]
    F4[" "]
    F5[" "]
    F6[" "]
    F7[" "]
    F8[" "]
    F9[" "]
    F10[" "]
    F11[" "]
```
