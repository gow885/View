mindmap
  root((w_about 政府信息表))
    Id int(11) 主键自增
    name varchar(50) 名称
    intro varchar(255) 简介
    about_type int(1) 类型
    company_name varchar(255) 公司名称
    img varchar(255) 图片
    plan varchar(50) 行业解决方案经验
    patent varchar(50) 产品外观及技术专利
    case varchar(50) 长期战略合作伙伴
    create_time Datetime 创建时间
    update_time Datetime 更新时间
