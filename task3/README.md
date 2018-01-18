
# 项目详情
你是一名业务分析师顾问，你的客户是一个电影制作新公司，他们将制作一部新电影。客户想确保电影能成功，从而使新公司立足市场。他们希望你能帮助他们了解电影市场趋势，使他们能做出正确的决策。他们提供了指导，希望你能研究以下三大领域：

- 问题 1：电影类型是如何随着时间的推移发生变化的？
- 问题 2： Universal Pictures 和 Paramount Pictures 之间的对比情况如何？
- 问题 3： 改编电影和原创电影的对比情况如何？(通过keywords变量中的based on novel字段来判断)
更重要的是，客户请你根据提供的数据，额外回答第四个问题。

### movies.csv 数据说明
- id：标识号  
- imdb_id：IMDB 标识号
- popularity：在 Movie Database 上的相对页面查看次数
- budget：预算（美元）
- revenue：收入（美元）
- original_title：电影名称
- cast：演员列表，按 | 分隔，最多 5 名演员
- homepage：电影首页的 URL
- director：导演列表，按 | 分隔，最多 5 名导演
- tagline：电影的标语
- keywords：与电影相关的关键字，按 | 分隔，最多 5 个关键字
- overview：剧情摘要
- runtime：电影时长
- genres：风格列表，按 | 分隔，最多 5 种风格
- production_companies：制作公司列表，按 | 分隔，最多 5 家公司
- release_date：首次上映日期
- vote_count：评分次数
- vote_average：平均评分
- release_year：发行年份
- budget_adj：根据通货膨胀调整的预算（2010 年，美元）
- revenue_adj：根据通货膨胀调整的收入（2010 年，美元）
