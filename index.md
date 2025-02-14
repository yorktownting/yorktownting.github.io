---
layout: homepage
---

## 关于我

- 目前于浙江大学攻读遥感与地理信息系统专业博士学位（预计2026年6月毕业）。

- 本科毕业于浙江大学地球科学学院，地理信息科学理学学士（2017.09 - 2021.06）。

## 研究兴趣

- **空间分析**：计量地理学、时空大数据分析与可视化
- **GeoAI**：研究深度学习方法与大模型在地理信息科学中的应用
- **GIS开发**：云原生GIS系统的架构设计与研发

## 成果

- A neural network model to optimize the measure of spatial proximity in geographically weighted regression approach: A case study on house price in Wuhan. 2024. International Journal of Geographical Information Science. 第一作者. https://doi.org/10.1080/13658816.2024.2343771

- Using an attention-based architecture to incorporate context similarity into spatial non-stationarity estimation. International Journal of Geographical Information Science. 2025. 学生一作. https://doi.org/10.1080/13658816.2025.2456556

- GNNWR: An open-source package of spatiotemporal intelligent regression methods for modeling spatial and temporal nonstationarity. Geoscientific Model Development. 2024. 共同一作. https://doi.org/10.5194/gmd-17-8455-2024

- 基于TD-GNNWR的武汉市房价因子空间非平稳性研究. 2024. 地理学报. 学生一作. https://doi.org/10.11821/dlxb202408005 

- 发明专利1项：《基于时空资产目录的跨源数据检索方法、介质及设备》

- 软件著作权6项：《时空大数据治理系统》，《遥感大数据管理服务系统》，《云原生时空信息可视化引擎软件》，《云原生时空信息数据引擎软件》，《云原生时空信息云平台》，《全时空对象大数据引擎软件》

## 项目经验  

### 国家重点研发计划：全球综合观测大数据知识化管理与服务平台研制
- 时间：2021.03 - 2022.04
- 主要工作：
     - 实现系统对遥感影像、矢量、流场等多模数据和计算模型的统一管理能力，以及可视化、在线计算等功能模块。
    - 基于Airflow等开源产品，在K8s底座上实现模型镜像编排与零代码在线计算。
    - 独立部署前后端项目及Nginx、Ceph、Redis、PgSQL、Elasticsearch、Harbor等中间件，并维护其相关业务代码。

### 国家重点研发计划：对象空间建模理论与时空大数据引擎  
- 时间：2021.12 - 2024.11
- 主要工作：
    - 参与设计时空大数据引擎的整体架构，实现对时空大数据的管理、服务和“数据-知识-模型”耦合的智能分析。
    - 开展云原生实践，将后端拆解为若干微服务以便开发分工，借助Jenkins实现前端代码的CI/CD。
    - 参与实现一套数据网络管理系统，通过JDBC、HTTP、STAC、S3等多种协议实现对互联网中数据的统一接入。

### 开源项目：时空智能回归模型库
- 项目地址：https://github.com/zjuwss/gnnwr
- 基于Pytorch开发维护一套用于时间/空间非平稳数据的回归建模模型库。
- PyPI库下载量已破万，GitHub仓库Star破百。