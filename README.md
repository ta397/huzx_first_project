# huzx_first_project
基于大数据的企业员工培训效果评估与分析系统
## 📖 项目概述

    一个完整的基于大数据技术的企业员工培训效果评估与分析系统。系统采用前后端分离架构，结合大数据处理技术，为企业提供科学的培训效果评估解决方案。

### 🎯 核心功能
- **多角色管理**：管理员、培训师、员工三级权限体系
- **培训全周期管理**：培训计划→课程管理→学习跟踪→效果评估
- **大数据分析**：使用Spark进行培训数据处理和模型构建
- **智能评估**：多维度评估体系（反应层、学习层、行为层、结果层）
- **可视化展示**：使用ECharts实现数据可视化看板
- **证书管理**：自动生成和颁发培训证书

## 🏗️ 技术栈

| 组件 | 技术选型 | 说明 |
|------|----------|------|
| **后端框架** | Django 3.2 + Django REST Framework | Python Web框架，快速开发API |
| **前端框架** | Vue.js 3 + Element Plus | 渐进式JavaScript框架 |
| **大数据处理** | Apache Spark 3.0 + PySpark | 分布式数据处理引擎 |
| **数据库** | MySQL 8.0 | 关系型数据库 |
| **数据可视化** | ECharts 5.0 | JavaScript可视化库 |
| **开发工具** | PyCharm, VS Code, Navicat | 开发环境 |
| **版本控制** | Git + GitHub | 代码管理 |

## 🚀 快速开始

### 环境要求
- Python 3.9+
- Node.js 16+
- MySQL 8.0+
- Java 8+ (Spark需要)

### 1. 克隆项目
```bash
git clone https://github.com/yourusername/employee-training-evaluation-system.git
cd employee-training-evaluation-system
