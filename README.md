![image](https://github.com/user-attachments/assets/1b9e017d-72b9-4cb8-a21e-602566bd9533)


# novelai-clip-token-counter
通过加载CLIP Tokenizer模型来计算文本的Tokens数量。使用HTML和JavaScript实现，无需后端服务器，可以直接在浏览器中运行。
# CLIP Token Counter

A lightweight web tool for calculating the total number of tokens processed by the CLIP Tokenizer model.

【中文说明：一个轻量级网页工具，用于计算CLIP Tokenizer模型处理文本时的Tokens总数】

## Introduction | 项目简介

This project provides a lightweight web interface for token calculation using the CLIP Tokenizer model. Built with HTML and JavaScript, it runs directly in the browser without requiring a backend server.

【本项目提供了一个轻量级的网页界面，通过CLIP Tokenizer模型计算文本的Tokens数量。使用HTML和JavaScript实现，可直接在浏览器中运行，无需后端服务器】

## Features | 功能特点

- Browser-based interface
- Real-time token calculation
- CLIP Tokenizer model support
- Pure frontend implementation

【功能特点：
- 基于浏览器的界面
- 实时计算Tokens数量
- 支持CLIP Tokenizer模型
- 纯前端实现】

## Installation & Setup | 安装和设置

1. Install http-server globally (if not already installed):
```bash
npm install -g http-server

Clone the repository:

bashCopygit clone https://github.com/suwadaimyojin/clip-token-counter.git

Navigate to the project directory:

bashCopycd clip-token-counter

Start the http-server:

bashCopyhttp-server

Open your browser and visit http://localhost:5500

【安装和设置：

全局安装 http-server（如果尚未安装）
克隆仓库
进入项目目录
启动 http-server
在浏览器中访问 http://localhost:5500】


Important Note: This project must be served through a web server (like http-server) due to CORS restrictions when loading the model files. Simply opening the HTML file directly in a browser will not work.

【重要提示：由于加载模型文件时的跨域限制，本项目必须通过网络服务器（如 http-server）来启动。直接在浏览器中打开 HTML 文件将无法正常工作】
