flowchart LR
    Center(("w_about 政府信息表"))

    Center --> A["Id int(11) 主键自增"]
    Center --> B["name varchar(50) 名称"]
    Center --> C["intro varchar(255) 简介"]
    Center --> D["about_type int(1) 类型"]
    Center --> E["company_name varchar(255) 公司名称"]
    Center --> F["img varchar(255) 图片"]
    Center --> G["plan varchar(50) 行业解决方案经验"]
    Center --> H["patent varchar(50) 产品外观及技术专利"]
    Center --> I["case varchar(50) 长期战略合作伙伴"]
    Center --> J["create_time Datetime 创建时间"]
    Center --> K["update_time Datetime 更新时间"]
