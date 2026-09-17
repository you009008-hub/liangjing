# 第三方软件与素材

自有代码采用 GPL-3.0-only；以下组件保留其原有许可。

- Godot：安装包包含当前项目使用的 Windows 引擎。MIT 许可全文及引擎报告的第三方版权/许可分别见 licenses/GODOT-LICENSE.txt 与 licenses/GODOT-THIRD-PARTY.json。官方源代码与发布记录：https://github.com/godotengine/godot 。本次未独立核验本地引擎与官方下载哈希的一致性。
- Node.js：安装包包含 v24.19.0；完整版权和第三方说明见 licenses/NODE-LICENSE.txt。对应官方源码：https://github.com/nodejs/node/tree/v24.19.0 。
- npm：安装包包含用于首次联网安装的 npm 工具及其依赖，各文件自带许可保持原样，汇总入口 licenses/NPM-LICENSE.txt。官方源码：https://github.com/npm/cli 。
- Inno Setup：安装器使用官方 7.1.0 编译器生成，许可见 licenses/INNO-LICENSE.txt，官方源码：https://github.com/jrsoftware/issrc 。
- DeepSeek Harness：安装包不捆绑已安装的 app/node_modules，首次启动按 runtime/harness/app/package-lock.json 在线安装。主包 @deepseek-ai/dsh 声明 MIT，Copyright (c) 2026 DeepSeek；其他依赖各有原始许可，不能用主包许可替代。锁文件依赖索引见 docs/DEPENDENCY_INVENTORY.json，其中含 LGPL 组件。
- WeKnora：连接用户自行部署的服务，不捆绑其服务端。
- 人物、家具及派生资源：维护者说明原图由助手生成；逐图生成记录尚未补齐，素材独立许可状态见 LICENSE_STATUS.md 与 docs/ASSET_INVENTORY.json。

本文件记录本次发布所提供的声明，不表示第三方许可证已经过法律审查。
