# OceanBase 数据库 DBA 入门教程

欢迎访问 OceanBase 数据库 DBA 入门教程，您可以在本仓库中查看 DBA 入门教程的文档。本文简单为您介绍 DBA 入门教程各章节包含的内容以及如何贡献文档。

* 文档介绍

* 贡献文档

## 文档介绍

DBA 教程根据操作流程由浅到深分为八个章节，各章节内容如下。

### 第一章：OceanBase 数据库概述

文档地址：[zh-CN/1.chapter-1-overview-of-the-oceanbase-database.md](zh-CN/1.chapter-1-overview-of-the-oceanbase-database.md)
介绍 OceanBase 数据库的特点、发展历史、业务案例等内容，并对社区版情况进行简单介绍，帮助用户了解 OceanBase 数据库。

### 第二章：如何部署 OceanBase 社区版

本章介绍如何手动和自动部署 OceanBase 社区版集群，包括单副本和三副本集群。主要包含如下内容。

* [2.1 部署准备](zh-CN/2.chapter-2-how-to-deploy-oceanbase-community-edition/2.2-1-deployment-preparation.md)：介绍部署 OceanBase 数据库所需软件、资源要求以及自动化部署的过程。

* [2.2 如何快速体验 OceanBase](zh-CN/2.chapter-2-how-to-deploy-oceanbase-community-edition/3.2-2-how-to-quickly-experience-oceanbase.md)：介绍如何通过 Docker 环境快速部署并启动 OceanBase 数据库。

* [2.3 如何规划 OceanBase 集群部署](zh-CN/2.chapter-2-how-to-deploy-oceanbase-community-edition/4.2-3-how-to-plan-the-oceanbase-cluster-deployment.md)：介绍部署 OceanBase 集群时如何规划架构、用户和目录。

* [2.4 如何初始化服务器环境](zh-CN/2.chapter-2-how-to-deploy-oceanbase-community-edition/5.2-4-how-to-initialize-the-server-environment.md)：介绍部署 OceanBase 集群前需要如何配置服务器环境。

* [2.5 如何安装 OBD 自动化部署软件](zh-CN/2.chapter-2-how-to-deploy-oceanbase-community-edition/6.2-5-how-to-install-obd-automated-deployment-software.md)：介绍如何安装并配置 OBD，方便后文使用 OBD 部署 OceanBase 数据库。

* [2.6 如何使用 OBD 自动化部署单节点集群](zh-CN/2.chapter-2-how-to-deploy-oceanbase-community-edition/7.2-6-how-to-automatically-deploy-a-single-node-cluster-using-obd.md)：介绍如何使用 OBD 部署并启动单节点 OceanBase 数据库。

* [2.7 如何使用 OBD 自动化部署多节点集群](zh-CN/2.chapter-2-how-to-deploy-oceanbase-community-edition/8.2-7-how-to-use-obd-to-deploy-a-multi-node-cluster.md)：介绍如何使用 OBD 部署并启动多节点 OceanBase 集群。

* [2.8 如何查看和修改 OceanBase 参数集群](zh-CN/2.chapter-2-how-to-deploy-oceanbase-community-edition/9.2-8-how-to-view-and-modify-the-parameter-cluster-of.md)：介绍如何通过命令行、参数文件、OBD 等方式查看和修改 OceanBase 集群的参数。

* [2.9 如何部署 OBAgent](zh-CN/2.chapter-2-how-to-deploy-oceanbase-community-edition/10.2-9-how-to-deploy-obagent.md)：介绍如何使用 OBD 部署并启动 OBAgent。

* [2.10 如何重启 OceanBase 集群](zh-CN/2.chapter-2-how-to-deploy-oceanbase-community-edition/11.2-10-how-to-restart-an-oceanbase-cluster.md)：介绍如何通过手动或 OBD 重启 OceanBase 集群。

* [2.11 （高级）如何手动部署 OceanBase 集群](zh-CN/2.chapter-2-how-to-deploy-oceanbase-community-edition/12.2-11-advanced-how-to-manually-deploy-an-oceanbase-cluster.md)：介绍如何手动部署 OceanBase 集群。

* [2.12 常见问题](zh-CN/2.chapter-2-how-to-deploy-oceanbase-community-edition/13.2-12-common-issues.md)：OceanBase 数据库部署过程中的常见问题。

* [2.13 附录](zh-CN/2.chapter-2-how-to-deploy-oceanbase-community-edition/14.2-13-appendix.md)：OceanBase 数据库的配置文件示例。

### 第三章：如何使用 OceanBase 社区版

本章介绍如何使用 OceanBase 数据库社区版进行业务开发。主要包含如下内容。

* [3.1 查看 OceanBase 集群资源的使用情况](zh-CN/3.chapter-3-how-to-use-oceanbase-community-edition/2.3-1-view-the-usage-of-the-oceanbase-cluster-resources.md)：介绍 OceanBase 数据库多租户原理以及创建租户前如何查看集群可用资源。

* [3.2 如何创建和连接 MySQL 租户](zh-CN/3.chapter-3-how-to-use-oceanbase-community-edition/3.3-2-how-to-create-and-connect-a-mysql-tenant.md)：以创建 MySQL 模式租户为例介绍如何创建用户租户。

* [3.3 如何连接租户](zh-CN/3.chapter-3-how-to-use-oceanbase-community-edition/4.3-3-how-to-connect-tenants.md)：介绍如何通过 MySQL 客户端、OBClient 客户端、ODC 客户端等工具连接租户。

* [3.4 如何对租户参数（或变量）进行设置](zh-CN/3.chapter-3-how-to-use-oceanbase-community-edition/5.3-4-how-to-set-tenant-parameters.md)：介绍如何修改用户租户参数和用户租户变量。

* [3.5 如何使用 MySQL 租户做常见数据库开发](zh-CN/3.chapter-3-how-to-use-oceanbase-community-edition/6.3-5-how-to-use-mysql-tenants-for-common-database-development.md)：以用户管理和数据库管理为例介绍如何使用用户租户做数据库开发。

* [3.6 如何使用 OceanBase 分区表进行水平拆分](zh-CN/3.chapter-3-how-to-use-oceanbase-community-edition/7.3-6-how-to-split-data-horizontally-with-oceanbase-partition-table.md)：介绍 OceanBase 数据库的分区路由、分区策略以及分区表的实践，帮助用户理解如何使用 OceanBase 数据库分区表进行水平拆分。

* [3.7 （高级）如何使用 OceanBase 表分组](zh-CN/3.chapter-3-how-to-use-oceanbase-community-edition/8.3-7-advanced-how-to-use-oceanbase-table-grouping.md)：简单介绍表分组，并举例介绍如何创建表分组。

* [3.8（高级）如何使用 OceanBase 复制表](zh-CN/3.chapter-3-how-to-use-oceanbase-community-edition/9.3-8-advanced-how-to-use-oceanbase-to-copy-tables.md)：介绍复制表的原理、语法和使用场景。

* [3.9 常见问题](zh-CN/3.chapter-3-how-to-use-oceanbase-community-edition/10.3-9-common-issues.md)：使用 OceanBase 数据库进行业务开发时的一些常见问题。

### 第四章：向 OceanBase 数据库迁移数据

本章使用不同的工具介绍如何将 MySQL 数据库数据迁移到 OceanBase 数据库，以及如何将 OceanBase 数据库数据迁移到 MySQL 数据库。主要包含如下内容。

* [4.1 OceanBase 的 MySQL 兼容性简介](zh-CN/4.4-0-migrate-data-to-an-oceanbase-database/2.4-1-mysql-compatibility-of-oceanbase.md)：从数据类型、SQL 语法、变量、字符集四个方面介绍 OceanBase 数据库和 MySQL 的兼容情况。

* [4.2 如何使用 mysqldump 迁移 MySQL 表到 OceanBase](zh-CN/4.4-0-migrate-data-to-an-oceanbase-database/3.4-2.md)：简单介绍如何使用 mysqldump 导出指定数据库的表结构和表数据。

* [4.3 如何使用 DBCAT 迁移 MySQL 表结构到 OceanBase](zh-CN/4.4-0-migrate-data-to-an-oceanbase-database/4.4-3-how-to-use-dbcat-to-migrate-mysql-table-structures.md)：介绍如何安装 DBCAT 并使用 DBCAT 迁移 MySQL 表结构到 OceanBase 数据库。

* [4.4 如何把 MySQL 表数据导出到 CSV 文件](zh-CN/4.4-0-migrate-data-to-an-oceanbase-database/5.4-4-how-to-export-data-from-a-mysql-table-to.md)：介绍如何将 MySQL 表数据导出为 CSV 文件，以及如何将导出的 CSV 文件导入 MySQL 数据库。

* [4.5 如何使用 OceanBase 的 LOAD 命令加载 CSV 数据文件 OceanBase](zh-CN/4.4-0-migrate-data-to-an-oceanbase-database/6.4-5-how-to-use-the-load-command-of-oceanbase-to.md)：介绍 load data 命令语法及原理，以及如何使用 load data 命令将 CSV 文件导入到 OceanBase 数据库。

* [4.6 如何使用 DataX 加载 CSV 数据文件到 OceanBase](zh-CN/4.4-0-migrate-data-to-an-oceanbase-database/7.4-6-how-to-use-datax-to-load-csv-data-files.md)：介绍在源端和目标端不能同时跟 DataX 服务器网络联通情况下，如何通过 DataX 加载源端 MySQL 导出的 CSV 文件，并将该文件导入到目标端 OceanBase 数据库中。

* [4.7 如何使用 DataX 迁移 MySQL数据到 OceanBase](zh-CN/4.4-0-migrate-data-to-an-oceanbase-database/8.4-7-migrate-mysql-data-to-oceanbase-by-using-datax.md)：介绍源端数据库和目标端数据库能同时跟 DataX 所在服务器联通的情况下，如何通过 DataX 将数据从源端迁移到目标端。

* [4.8 如何使用 OBDUMPER / OBLOADER 工具导出/导入 OceanBase 数据](zh-CN/4.4-0-migrate-data-to-an-oceanbase-database/9.4-8-how-to-use-obdumper-obloader-to-export-import.md)：介绍如何通过 OBDUMPER 导出 OceanBase 数据库结构或数据，以及如何通过 OBLOADER 工具导入 OceanBase 数据库结构或数据。

* [4.9 如何使用 DataX 迁移 OceanBase 数据到 MySQL/ORACLE](zh-CN/4.4-0-migrate-data-to-an-oceanbase-database/10.4-9-how-to-migrate-data-from-oceanbase-to-mysql-or.md)：介绍如何使用 DataX 工具迁移 OceanBase 数据库数据到 MySQL 或 Oracle 数据库。

* [4.10 如何使用 Canal 将 MySQL 数据实时同步到 OceanBase](zh-CN/4.4-0-migrate-data-to-an-oceanbase-database/11.4-10-how-to-use-canal-to-synchronize-mysql-data-to.md)：介绍如何使用 Canal 将 MySQL 数据库数据实时同步到 OceanBase 数据库。

* [4.11 如何使用 Canal 将 OceanBase 数据实时同步到 MySQL](zh-CN/4.4-0-migrate-data-to-an-oceanbase-database/12.4-11-how-to-use-canal-to-synchronize-ob-data-to.md)：介绍如何使用 Canal 将 OceanBase 数据库数据实时同步到 MySQL 数据库。

* [4.12 如何对 OceanBase 迁移性能进行简单分析和调优](zh-CN/4.4-0-migrate-data-to-an-oceanbase-database/13.4-12-how-to-analyze-and-optimize-the-performance-of-oceanbase.md)：介绍如何对 OceanBase 数据库迁移性能进行分析和调优。

* [4.13 如何使用 CloudCanal 迁移和实时同步数据到 OceanBase](zh-CN/4.4-0-migrate-data-to-an-oceanbase-database/14.4-13-how-to-use-cloudcanal-to-migrate-and-realtime-sync-data-to-oceanbase.md)：以迁移 MySQL 数据库为例，介绍如何使用 CloudCanal 迁移和实时同步源端数据到 OceanBase 数据库。

### 第五章：运维 OceanBase 数据库

本章介绍如何对 OceanBase 数据库进行运维，包括集群扩缩容、重启、备份、监控，租户扩缩容、性能调优等。主要包含如下内容。

* [5.1 如何管理 OceanBase 集群](zh-CN/5.5-0-o-m-oceanbase-database/2.5-1-how-to-manage-an-oceanbase-cluster.md)：介绍 OceanBase 数据库集群架构、如何管理 OceanBase 集群参数和数据库内存，帮助大家更好的了解 OceanBase 数据库。

* [5.2 如何管理 OceanBase 租户](zh-CN/5.5-0-o-m-oceanbase-database/3.5-2-how-to-manage-oceanbase-tenants.md)：介绍 OceanBase 数据库租户原理以及如何管理租户，包括修改租户变量、修改租户参数、对租户资源扩缩容等。

* [5.3 如何对 OceanBase 进行备份和恢复](zh-CN/5.5-0-o-m-oceanbase-database/4.5-3-how-to-back-up-and-restore-oceanbase.md)：介绍 OceanBase 数据库备份恢复的概念，并结合示例介绍如何发起 OceanBase 集群备份、如何发起 OceanBase 数据库租户恢复。

* [5.4 如何监控 OceanBase 和配置告警](zh-CN/5.5-0-o-m-oceanbase-database/5.5-4-monitor-oceanbase-and-configure-alerts.md)：介绍如何使用 Prometheus 监控 OceanBase 数据库。

* [5.5 如何对 OceanBase 进行简单性能诊断](zh-CN/5.5-0-o-m-oceanbase-database/6.5-5-how-to-perform-performance-diagnosis-for-oceanbase.md)：介绍如何使用 Tsar 实时监控 OceanBase 数据库主机性能、如何使用 DOOBA 实时监控 OceanBase 数据库租户性能，以及如何对 OceanBase 租户内存进行调优。

* [5.6 如何快速处理 OceanBase 故障](zh-CN/5.5-0-o-m-oceanbase-database/7.5-6-how-to-quickly-troubleshoot-oceanbase-faults.md)：介绍当 OceanBase 数据库故障时如何定位判断，并介绍如何处理节点掉线或宕机故障，如何处理节点时间不同步故障。

* [5.7 如何使用 OBD 运维](zh-CN/5.5-0-o-m-oceanbase-database/8.5-7-how-to-use-obd-based-o-m.md)：介绍如何使用 OBD 调整 OceanBase 集群参数、对 OceanBase 集群扩容。

* [5.8 附录](zh-CN/5.5-0-o-m-oceanbase-database/9.5-8-appendix.md)：介绍 OBAgent 常用指标的查询表达式。

### 第六章：测试 OceanBase 数据库

本章介绍如何对 OceanBase 进行性能测试，主要包含如下内容。

* [6.1 性能测试概述](zh-CN/6.6-0-test-oceanbase-database/2.performance-testing-overview.md)：简单介绍性能测试的标准，以及 OceanBase 数据库对故障的应对能力。

* [6.2 影响性能的因素](zh-CN/6.6-0-test-oceanbase-database/3.6-2-factors-affecting-performance.md)：介绍影响性能的因素，如磁盘的划分、OceanBase 数据库和 ODP 的参数设置、转储与合并、是否使用分区表等。

* [6.3 如何运行 Sysbench 测试](zh-CN/6.6-0-test-oceanbase-database/4.6-3-how-to-run-the-sysbench-test.md)：结合示例讲解如何执行 Sysbench 测试，并介绍一些性能调优经验。

* [6.4 如何运行 TPC-C 测试](zh-CN/6.6-0-test-oceanbase-database/5.6-4-how-do-i-run-the-tpc-c-test.md)：结合示例讲解如何执行 TPC-C 测试，并介绍一些性能调优经验和常见问题的处理方法。

* [6.5 如何运行 TPC-H 测试](zh-CN/6.6-0-test-oceanbase-database/6.6-5-how-do-i-run-tpc-h-tests.md)：结合示例讲解如何执行 TPC-H 测试，并介绍一些性能调优经验。

* [6.6 如何使用 JMeter 运行业务场景测试](zh-CN/6.6-0-test-oceanbase-database/7.6-6-how-to-use-testing-in-running-business-scenarios.md)：结合示例讲解如何使用 JMeter 执行业务场景测试。

### 第七章：OceanBase 数据库性能诊断和调优

本章介绍 OceanBase 性能诊断和调优技巧以及部分原理，主要包含如下内容。

* [7.1 性能诊断调优概述](zh-CN/7.chapter-7-diagnosing-and-tuning-oceanbase-performance/2.01-overview-of-performance-diagnosis-and-optimization.md)：简单介绍 SQL 引擎和 OceanBase 数据库性能诊断通常方向。

* [7.2 OBProxy SQL 路由原理](zh-CN/7.chapter-7-diagnosing-and-tuning-oceanbase-performance/3.7-2-obproxy-sql-routing-principles.md)：介绍如何查看数据位置，以及 ODP 的 SQL 路由原理。

* [7.3 如何管理 OceanBase 数据库连接](zh-CN/7.chapter-7-diagnosing-and-tuning-oceanbase-performance/4.03-how-to-manage-the-oceanbase-database-connection.md)：根据连接 OceanBase 数据库的不同连接方法介绍如何管理 OceanBase 数据库连接。

* [7.4 如何分析 SQL 审计视图](zh-CN/7.chapter-7-diagnosing-and-tuning-oceanbase-performance/5.7-4-how-to-analyze-the-sql-audit-view.md)：简单介绍 SQL 审计视图的概念，以及如何查看 SQL 审计视图。

* [7.5 如何诊断和调优 OceanBase SQL 执行计划](zh-CN/7.chapter-7-diagnosing-and-tuning-oceanbase-performance/6.7-5-how-to-diagnose-and-tune-the-oceanbase-sql-execution.md)：介绍如何使用 EXPLAIN 查看理论执行计划，以及如何查看、改变实际执行计划。

### 第八章：OceanBase 生态工具介绍

本章简单介绍 OceanBase 相关的工具、产品等用法。主要包含如下内容。

* [8.1 主机监控产品](zh-CN/8.chapter-8-introduction-to-oceanbase-ecological-tools/2.8-1-host-monitoring-products.md)：简单介绍主机监控产品，如 Tsar。更多工具欢迎大家补充。

* [8.2 数据迁移产品](zh-CN/8.chapter-8-introduction-to-oceanbase-ecological-tools/3.8-2-data-migration-products.md)：简单介绍数据迁移产品，如 DataX、Canal。更多工具欢迎大家补充。

* [8.3 运维工具](zh-CN/8.chapter-8-introduction-to-oceanbase-ecological-tools/4.8-3-o-m-tools.md)：简单介绍运维工具，如 DOOBA、ob_admin 工具、ob_error 工具、Addr2line 工具。更多工具欢迎大家补充。

### 附录：教程文档贡献者

文档地址：[zh-CN/9.appendix-tutorial-document-contributors.md](zh-CN/9.appendix-tutorial-document-contributors.md)

该文档主要介绍该教程写作中的贡献者，诸位老师均通过问答区或 GitHub 仓库为该教程捉虫或提交 PR。

## 贡献文档

### 开始之前

感谢您对 OceanBase 数据库文档的贡献兴趣。为厘清就个人或实体贡献内容而授予的知识产权许可，我们必须对每位贡献者签署的贡献者许可协议（Contributor Licence Agreement，简称 CLA）（“CLA”）进行归档，以证明就CLA达成的一致。点击 [OceaBase CLA](https://cla-assistant.io/oceanbase/oceanbase?pullRequest=108)，点击 **Sign in with GitHub to agree** 按钮签署协议。

### 贡献指南

您可以按照以下步骤提交 Pull Request（简称 PR）：

#### 步骤 1：Fork 项目仓库

1. 访问 OceanBase 数据库 DBA 入门教程文档的 [GitHub 地址](https://github.com/oceanbase/tutorials-doc)。

2. 点击 Fork 按钮创建远程分支。

#### 步骤 2：克隆分支到本地

1. 定义工作目录。

   ```shell
   # 定义工作目录
   working_dir=$HOME/Workspace
   ```

2. 配置 GitHub 用户名。

   ```shell
   user={GitHub账户名}
   ```

3. 克隆代码。

   ```shell
   # 克隆代码
   mkdir -p $working_dir
   cd $working_dir
   git clone git@github.com:$user/tutorials-doc.git
   # 或: git clone https://github.com/$user/tutorials-doc.git

   # 添加上游分支
   cd $working_dir/tutorials-doc
   git remote add upstream git@github.com:oceanbase/tutorials-doc.git
   # 或: git remote add upstream https://github.com/oceanbase/tutorials-doc.git

   # 为上游分支设置 no_push
   git remote set-url --push upstream no_push

   # 确认远程分支有效
   git remote -v
   ```

#### 步骤 3：创建新分支

1. 更新本地分支。

   ```shell
   cd $working_dir/tutorials-doc
   git fetch upstream
   git checkout $branch
   git rebase upstream/$branch
   ```

2. 基于本地 $branch 分支创建新分支。

   ```shell
   git checkout -b new-branch-name
   ```

#### 步骤 4：修改/添加/删除文档

在 `new-branch-name` 上修改文档并保存更改。

#### 步骤 5：提交更改

```shell
# 检查本地文件状态
git status

# 添加您希望提交的文件
# 如果您希望提交所有更改，直接使用 `git add .`
git add <file> ...
git commit -m "commit-message: update the xx"
```

#### 步骤 6：保持开发分支与上游分支同步

```shell
# 在开发分支执行以下操作
git fetch upstream
git rebase upstream/branch
```

#### 步骤 7：推送更改至远程分支

```shell
# 在开发分支执行以下操作
git push -u origin new-branch-name
```

#### 步骤 8：创建 PR

1. 访问您 Fork 的仓库。

2. 单击 `new-branch-name` 分支旁的 `Compare & pull request` 按钮。

以上就是参与 OceanBase 数据库文档共建的步骤，如果在此过程中遇到任何问题，可以加入我们唯一官网钉钉群：41203246，与社区热心的技术大神、热情的贡献者、经验丰富的技术专家一起交流、探讨问题。
