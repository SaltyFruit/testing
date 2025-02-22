# openEuler 22.03 RISC-V 版本 MySQL 特性测试

# 1. 测试目的

使用 openEuler 22.03 RISC-V 版本镜像，测试 MySQL 的安装和基本功能运行是否正常。

# 2. 测试信息

## 2.1 被测对象的版本信息

| 版本名称 | 更新时间 | 测试起始时间 | 测试结束时间 |
|----------|----------|--------------|--------------|
| MySQL    |          |   20230115           |    20230228          |

## 2.2 硬件环境信息

| 硬件型号  | 硬件配置信息                            | 备注        |
|-----------|-----------------------------------------|-------------|
| RISC-V 64 | CPU核数：4<br>内存：8G<br>硬盘容量：10G | QEMU 模拟器 |

# 3. 测试内容概述

## 3.1 测试内容

| 测试内容 | 测试要求                                      |
|----------|-----------------------------------------------|
| 安装测试 | 在 openEuler RISC-V QEMU 模拟器上安装 MySQL。 |
| 功能测试 | 覆盖测试点，MySQL 基本功能运行正常。          |
| 专项测试 | 无                                            |

## 3.2 约束说明

- [安装说明](./MySQL_installation_guide.md)
- [使用说明](./MySQL_userguide.md)

## 3.3 测试要求

- 应根据测试点要求，编写测试用例，进行测试。

- 应使用提供的[测试报告模板](./测试报告模板.md)编写测试用例，操作步骤、应有充分文字描述和屏幕截图。

- 应使用提供的[缺陷报告模板](./缺陷报告模板.md)编写缺陷报告，基本情况、环境信息、缺陷描述、准备过程、操作步骤、结果（预期结果和实际结果）、其他说明、测试人员名单。

- 应提交测试用例和缺陷报告。

# 4. 测试执行

## 4.1 测试用例模板

### 测试用例名称

    使用帮助：
    使用截图：

*以上内容为必填项，完整[测试报告模板](./测试报告模板.md)*

## 4.2 缺陷报告模板

### 缺陷名称

    缺陷描述：
    操作步骤：
    预期结果：
    实际结果：

*以上内容为必填项，完整[缺陷报告模板](./测试报告模板.md)*
