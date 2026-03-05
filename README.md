# Augment Token Manager

基于 Tauri 的跨平台桌面应用，用于管理 Augment/OpenAI 相关账号与令牌。

## 最近更新

- 新增 `Codex` 账号文件批量导入功能。
- 支持标准 OpenAI 对话接口：`/v1/chat/completions`。

## 主要功能

- Augment 授权流程辅助与 Token 管理。
- 多账号管理（新增、编辑、删除、导入）。
- OpenAI/Codex 平台配置与状态管理。

## 安装

- Release 下载地址：<https://github.com/libaxuan/augment-token-mng/releases>

## 开发环境

1. 安装 Node.js（建议 LTS 版本）
2. 安装 Rust（<https://rustup.rs>）
3. 安装依赖并启动开发模式

```bash
npm install
npm run tauri dev
```

## 构建

```bash
npm install
npm run tauri build
```

## 使用说明（简版）

1. 在应用内完成 Augment 授权并获取 Token。
2. 在账号管理页面维护各平台账号。
3. 通过导入功能批量导入 Codex/OpenAI 账号文件。
4. 使用标准 OpenAI Chat Completions 接口进行对话。

## 许可证

MIT License
