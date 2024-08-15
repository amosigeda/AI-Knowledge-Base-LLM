

# Quickly Create Professional AI Applications

Try it now
http://101.126.22.66:3000/login

## Introduction

This project is designed to help you quickly create professional AI applications. You can control the responses of the AI and integrate it into any system. By training the AI, it can better understand your knowledge, helping you build your own exclusive knowledge base. Additionally, this project supports on-premise deployment to ensure the security of your data.
It provides out-of-the-box data processing, model calling, RAG retrieval, visual AI workflow orchestration and other capabilities to help you easily build complex AI applications and train enterprise knowledge bases. Training personal knowledge bases

## Features

- **Professional Capability**: Supports custom training to control AI responses.
- **System Integration**: Can be integrated into DingTalk, Lark, WeChat Work, WhatsApp, Telegram, and any other systems.
- **On-Premise Deployment**: Supports on-premise deployment to protect your data privacy.
- **API Access**: Provides API interface for easy integration into your applications.

## API Example

You can use the following API to interact with the knowledge base:

### API Endpoint

`POST http://localhost:3000/api/v1/chat/completions`

### Request Parameters

```json
{
    "chatId": "abcd",
    "stream": false,
    "detail": false,
    "variables": {
        "uid": "dad",
        "name": ""
    },
    "messages": [
        {
            "content": "Who are you?",
            "role": "user"
        }
    ]
}
```

### Response Example

```json
{
    "id": "abcd",
    "model": "",
    "usage": {
        "prompt_tokens": 1,
        "completion_tokens": 1,
        "total_tokens": 1
    },
    "choices": [
        {
            "message": {
                "role": "assistant",
                "content": "I am a robot."
            },
            "finish_reason": "stop",
            "index": 0
        }
    ]
}
```

## Integration

You can integrate the AI application into the following platforms via the API:

- DingTalk
- Lark
- WeChat Work
- WhatsApp
- Telegram
- And any other systems that support API calls

## Documentation

You can train the AI with specific content using the provided documentation. Please refer to the documentation for detailed steps.

## Contact Information

- **Email**: zhenzhikeji988233@outlook.com
- **WeChat**: w85988233


************************************************************************************************************************************************************************************************************************************************************************


# 快速创建拥有专业能力的 AI 应用

欢迎试用
http://101.126.22.66:3000/login

## 简介

本项目旨在帮助您快速创建一个拥有专业能力的 AI 应用，支持控制 AI 的回答内容，并能接入到任何系统中。通过训练 AI，让它更懂您的知识，构建属于您的专属知识库。此外，本项目支持私有化部署，确保您的数据安全。
提供了开箱即用的数据处理、模型调用、RAG 检索、可视化 AI 工作流编排等能力，帮助您轻松构建复杂的 AI 应用,企业知识库的训练。个人知识库的训练

## 特性

- **专业能力**：支持自定义训练，控制 AI 回答内容。
- **系统集成**：可接入到钉钉、飞书、企业微信、WhatsApp、Telegram 等任意系统。
- **私有化部署**：支持私有化部署，保障您的数据隐私。
- **API 调用**：提供 API 接口，轻松集成到您的应用中。

## API 示例

您可以通过以下 API 进行知识库的调用：

### API Endpoint

`POST http://localhost:3000/api/v1/chat/completions`

### 请求参数

```json
{
    "chatId": "abcd",
    "stream": false,
    "detail": false,
    "variables": {
        "uid": "dad",
        "name": ""
    },
    "messages": [
        {
            "content": "你是谁？",
            "role": "user"
        }
    ]
}
```

### 返回结果

```json
{
    "id": "abcd",
    "model": "",
    "usage": {
        "prompt_tokens": 1,
        "completion_tokens": 1,
        "total_tokens": 1
    },
    "choices": [
        {
            "message": {
                "role": "assistant",
                "content": "我是一个机器人。"
            },
            "finish_reason": "stop",
            "index": 0
        }
    ]
}
```

## 集成说明

您可以通过 API 接口将本项目的 AI 应用集成到以下平台：

- 钉钉
- 飞书
- 企业微信
- WhatsApp
- Telegram
- 以及任何其他支持 API 调用的系统
- 微信

## 文档

您可以使用文档进行 AI 的内容训练，具体操作请参考文档中的详细步骤。

## 联系方式

- **邮箱**: zhenzhikeji988233@outlook.com
- **微信**: w85988233
