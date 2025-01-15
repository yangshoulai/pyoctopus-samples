# pyoctopus-samples

## 项目简介

pyoctopus-samples 是一个 Python 爬虫示例集合，展示了使用 pyoctopus 爬虫框架的各种实际应用场景。本项目旨在帮助开发者快速上手 pyoctopus，并提供多个实用的爬虫案例作为参考。

## 示例列表

### 网站爬虫

- **豆瓣电影** (samples/douban.py)

  - 爬取豆瓣电影信息
  - 支持电影详情、评分、评论等数据获取

- **4K 高清图片** (samples/4khd.py)

  - 支持高清图片批量下载
  - 自动创建目录并保存图片

- **秀人网** (samples/xiurenwang.py)

  - 图集爬取
  - 支持分页和批量下载

- **妹子图** (samples/mzt.py)

  - 图片资源爬取
  - 支持多线程下载

- **Gitee** (samples/gitee.py)
  - 码云仓库信息爬取
  - API 调用示例

### 工具示例

- **日志配置** (samples/sample_logging.py)
  - 展示如何配置和使用日志
  - 包含不同级别的日志记录示例

## 环境要求

- Python 3.7+
- 相关依赖包（见 requirements.txt）

## 快速开始

1. 克隆项目

```bash
git clone https://github.com/yourusername/pyoctopus-samples.git
cd pyoctopus-samples
```

2. 安装依赖

```bash
pip install -r requirements.txt
```

3. 运行示例

```bash
# 运行豆瓣爬虫示例
python samples/douban.py

# 运行4K图片下载示例
python samples/4khd.py
```

## 使用说明

### 基本配置

每个爬虫示例都可以独立运行，使用前请确保：

1. 已安装所有依赖
2. 了解目标网站的使用政策
3. 配置了正确的请求参数（如需要）

### 注意事项

- 遵守网站的 robots.txt 规则
- 合理设置请求间隔，避免对目标站点造成压力
- 注意数据的合法使用，遵守相关法律法规
- 建议使用代理池避免 IP 被封禁

## 开发指南

### 目录结构

```
pyoctopus-samples/
├── README.md
├── requirements.txt
└── samples/
    ├── __init__.py
    ├── douban.py
    ├── 4khd.py
    ├── xiurenwang.py
    ├── mzt.py
    ├── gitee.py
    └── sample_logging.py
```

### 开发新示例

1. 在 samples 目录下创建新的 Python 文件
2. 参考现有示例的代码结构
3. 确保代码符合 PEP 8 规范
4. 添加必要的注释和文档

## 贡献指南

欢迎提交 Pull Request 来完善示例或添加新的爬虫示例。提交时请：

1. 确保代码风格符合项目规范
2. 添加必要的注释和文档
3. 更新 README.md（如需要）

## 许可证

本项目采用 MIT 许可证，详见 [LICENSE](LICENSE) 文件。

## 免责声明

本项目仅供学习交流使用，请勿用于非法用途。对于使用本项目进行任何违法活动所造成的后果，本项目概不负责。
