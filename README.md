# 梁鲸桌面助手
就是个桌宠版本的deepseek harness
基于 Godot 的 Windows 桌面智能助手，整合人物互动、AI 对话、模型配置、知识库与任务执行。

**当前版本：0.1.0-alpha.1（公开测试版）。**

## 下载

进入 [Releases 下载页](https://github.com/you009008-hub/liangjing/releases) 获取 Windows x64 安装包、对应源码与 SHA256 校验文件。首次启动需要联网安装锁定的 Harness 依赖，然后在模型中心配置自己的服务。

完整源码也保存在本仓库的 [Liangjing-0.1.0-alpha.1-source.zip](Liangjing-0.1.0-alpha.1-source.zip)。首次发布通过网页上传归档，代码尚未逐文件导入 Git；解压其中的 `source-candidate` 目录即可查看全部代码、构建脚本、资源、依赖锁文件及开发说明。GitHub 自动生成的 Source code 包是仓库外层文件，请优先下载上述同名源码附件。

## 功能

- 桌宠分层动态、屏幕边缘停靠、换装生成及衣柜。
- 对话历史、模型配置、审批与追问，连接 DeepSeek Harness 执行任务。
- 连接已有 WeKnora 服务，工作流支持知识库检索与知识问答。
- 可视化节点编排、顺序执行、运行记录与工作流分享。
- Windows 原生功能窗口和异步文件选择。

工作流目前执行顺序链；分支、合流与循环只能保存，服务器工作流市场尚未接入。图像服务、模型和知识库需要自行配置，可能产生服务费用，不提供共享 Key。

## 许可与验证

自有代码采用 [GPL-3.0-only](LICENSE)：允许商用，分发修改版须遵守对应源码提供等义务。图片许可范围另见 [LICENSE_STATUS.md](LICENSE_STATUS.md)，第三方组件保留原许可，见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。上述文档中的 `docs/`、`licenses/` 路径位于源码压缩包内。

正式源码 36 组回归、bootstrap 6 项测试通过，隔离便携安装的 1,942 个文件已逐项核对。安装器未签名；普通安装/卸载、新电脑、DPI、多显示器和真实服务兼容性仍需验收。素材逐图生成记录及独立许可待补齐。详情见 [发布验证范围](RELEASE_READINESS.md)。

普通问题请提交 Issue；不要公开 API Key、私人会话或完整安全漏洞利用内容。
