# Dify-企微机器人
## Dify-Enterprise-WeChat-bot

![Logo](https://github.com/luolin-ai/Dify-Enterprise-WeChat-bot/assets/135555634/79509f35-2c98-4742-8860-006d286cb694)

## 📌 介绍

欢迎来到 **Dify-企业微信机器人** 仓库！这是一个专为企业微信设计的知识库聊天机器人，利用 Dify API 增强其功能。兼容企业微信最新版本 4.1.13.6009，特别是针对外部群组的新功能。

🔗 [下载企业微信 4.1.13.6009](https://dldir1.qq.com/wework/work_weixin/WeCom_4.1.22.6009.exe)

## ✨ 核心功能

- **上下文管理**：借助 Dify API，实现聊天上下文的维护，使机器人可以无缝处理复杂对话。
- **独立会话管理**：为企业微信群聊中的每个用户维护独立的会话，实现个性化互动。
- **智能回复**：通过改进的 AI 算法，提供更准确的响应，增强用户体验。
- **聊天记录功能**：自动记录聊天内容，方便回顾与进一步的 AI 训练。
- **配置灵活性**：用户可以通过配置文件自定义机器人的行为，如上下文管理和会话处理。
- **持续优化**：定期推出新功能和性能优化，不断提升机器人的表现。

## 🚀 最近更新

### 2024/05/20

- 废除原有版本，采用官网最新版本，新版沿用 win 方式登录，大幅降低风险，目前测试有半年安全无风险。
- 新增私有化部署本地 Dify 对接企微。可配置值：
  - `true`：连接到本地部署的 Dify 服务，适用于本地开发和测试。
  - `false`：连接到 Dify 官网服务，适用于生产环境或当本地服务器不可用时。

### 2024/04/27

- ~~PAD协议登录~~：新的登录协议，显著降低安全风险。
- **完全兼容**：支持最新的 Dify 工作流程和 API。
- **聊天记录输出**：优化输出格式，支持数据的二次训练。
- **上下文关联**：强化与 Dify 后台的数据关联，实现高效的会话管理。

## 🔜 即将推出的功能

- 语音转文本及语音识别功能
- Dify 图像识别和文件发送功能
- 自动基于用户对话进行知识库训练，实现机器人的自我学习和迭代
- 批量添加好友功能

## 🛠️ 安装和配置

### 配置 Dify Key

1. 创建一个 `.env` 文件，并添加您的 Dify Key：

    ```bash
    echo "YOUR_DIFY_KEY_HERE" > .env
    ```

### 快速开始

1. **打开 Dify 官网并登录**

    ![登录](https://github.com/luolin-ai/Dify-Enterprise-WeChat-bot/assets/135555634/79509f35-2c98-4742-8860-006d286cb694)

2. **创建自己的应用**

    ![创建应用](https://github.com/luolin-ai/Dify-Enterprise-WeChat-bot/assets/135555634/f871a335-012b-4d43-af4f-1851c3ad2534)

3. **选择对话型应用**

    ![选择对话型应用](https://github.com/luolin-ai/Dify-Enterprise-WeChat-bot/assets/135555634/58b5010d-996d-430a-abe8-41066814c7b4)

4. **生成自己的应用 Key**

    ![生成应用 Key](https://github.com/luolin-ai/Dify-Enterprise-WeChat-bot/assets/135555634/2961ed63-bc6c-4a71-ab8e-88be9d424c27)

5. **打开项目的配置文件填写自己的 Dify Key**

    ![填写 Key](img_1.png)

6. **运行项目的 app 软件**

    ![运行项目](https://github.com/luolin-ai/Dify-Enterprise-WeChat-bot/assets/135555634/fecd6610-3462-4137-b420-ba98cbb9058f)

## 💬 Dify 企微机器人项目交流群

添加小助手入群加微信备注 Dify

![微信群](https://github.com/luolin-ai/Dify-Enterprise-WeChat-bot/assets/135555634/279afe8d-c602-4dcb-b16c-f0d7fdc4b23d)
