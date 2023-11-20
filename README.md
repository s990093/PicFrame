# PicFrame

製作一個小照片播放圖片的小工具

项目介绍
Photo Hub 是一个多层次的项目，旨在创建一个可通过 Web 界面上传和展示照片的系统。该系统由 Next.js、Django 和 ESP32 等技术构建，涵盖前端、后端和嵌入式设备的多个方面。

主要特性
Next.js 前端： 使用 TypeScript 和 Next.js 构建现代、响应式的用户界面，支持照片上传和实时展示。

Django 后端： 基于 Django 框架，提供强大的后端支持，包括用户身份验证、数据存储和 API 管理。

ESP32 嵌入式设备： 集成 ESP32 微控制器，通过 Wi-Fi 连接到后端，可以实现从设备上传照片到系统中。

如何启动
Next.js 前端：

进入 frontend 目录。
运行 yarn install 安装依赖。
运行 yarn dev 启动开发服务器。
访问 http://localhost:3000 查看前端应用。
Django 后端：

进入 backend 目录。
运行 pip install -r requirements.txt 安装 Python 依赖。
运行 python manage.py runserver 启动 Django 开发服务器。
后端将运行在 http://localhost:8000。
ESP32 嵌入式设备：

使用 Arduino IDE 打开 esp32_photo_uploader.ino。
修改 Wi-Fi 配置和服务器地址。
将代码上传到 ESP32 设备。
设备将连接到服务器，并可以上传照片。
注意事项
确保您的开发环境中安装了 Node.js、Python、Arduino IDE 等必要的工具。
在配置文件中设置正确的数据库和服务器信息。
项目需要 Internet 连接以实现上传和下载照片功能。
