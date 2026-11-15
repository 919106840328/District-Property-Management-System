# District Property Management System

小区物业管理系统的 Eclipse / Java Web 工程骨架。仓库里目前**没有完整业务代码**，主要是 Eclipse 工程文件和 Hibernate 配置。

## 现有文件

| 路径 | 说明 |
|------|------|
| `.project` / `.classpath` | Eclipse 工程（工程名 `design`） |
| `.src/hibernate.cfg.xml` | Hibernate 3 + MySQL，库名 `communitysystem`，映射 `community/entity/Login` |

## 技术栈（按配置推断）

- Java（Eclipse + MyEclipse 部署插件）
- Hibernate ORM
- MySQL（连接库 `communitysystem`）

## 说明

本仓库不能直接编译运行。若要继续开发，需要补齐 Java 源码、Web 部署描述与实体类。

配置文件里的数据库账号口令不要当作真实生产凭证使用；若那台 MySQL 仍在用，请改密。
