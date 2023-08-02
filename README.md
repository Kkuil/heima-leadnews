# 黑马在线头条微服务项目

该项目是基于前沿技术栈开发的高效新闻资讯平台，旨在提供全面的新闻资讯服务。使用Spring Boot、Redis、Kafka和MinIO等技术来实现各种功能。

## 技术栈

- Spring Boot：快速构建微服务应用程序的框架。
- Redis：高性能缓存数据库，用于提高系统的响应速度和性能。
- Kafka：高吞吐量、可扩展的分布式消息系统，用于实现消息的异步处理和解耦。
- MinIO：开源的分布式对象存储服务，用于存储和管理大规模的非结构化数据。

## 功能

- **CRUD操作**：实现了文章的创建、读取、更新和删除功能。
- **分页查询**：提供了按页查询文章的接口，方便用户浏览大量文章。
- **关键字搜索**：支持根据关键字搜索文章，帮助用户快速找到感兴趣的内容。
- **热度排序**：根据文章的热度进行排序，让用户优先看到热门文章。
- **图片和文件存储**：使用MinIO存储用户上传的图片和文件，并提供下载接口。

## 如何使用

1. 在本地环境安装并配置Spring Boot、Redis、Kafka和MinIO。
2. 克隆该项目到本地。
3. 在项目根目录运行 `mvn spring-boot:run` 启动应用程序。
4. 访问 `http://localhost:8080` 即可开始使用黑马在线头条微服务项目。

## 贡献

欢迎对该项目进行贡献！如果您发现任何问题或有任何改进建议，请提交 Issue 或 Pull Request。

## 许可证

该项目使用 MIT 许可证。详细信息请参阅 [LICENSE](LICENSE) 文件。

## 鸣谢

感谢所有为该项目做出贡献的人！