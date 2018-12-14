# spring_cloud_web_spider_pro_repo
配置仓库(稳定环境)
配置文件为yml，config client 使用service-id作为配置获取地点时，不能用on 作为{profiles}会被解析为true,举栗子：server-on.yml 会被解析为server-true.yml,而缓存到本地文件中的为server-on.yml
应用启动会查询 server-true.yml.无法获取到。
