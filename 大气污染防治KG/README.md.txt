# 大气污染防治法律法规与标准知识图谱
参照：https://github.com/cxcygzs/Learning_ResourcesForGraduates

## 项目介绍
构建大气污染防治法规、国家标准、行业标准知识图谱，实现：
- 法规爬取
- 文本清洗
- 实体抽取
- 关系抽取
- Neo4j 图谱构建
- 可视化展示

## 目录结构
- Code：爬虫、处理、图谱代码
- Data：原始数据、处理数据、图谱数据
- Document：文档说明

## 运行步骤
1. pip install -r requirements.txt
2. 运行 crawl.py
3. 运行 clean.py
4. 运行 ner_extract.py
5. 运行 relation_extract.py
6. 运行 neo4j_import.py
7. 运行 visualize.py
