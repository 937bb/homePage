
简体中文 | [English](./README_EN.md)

> [!IMPORTANT]
> ## 声明
> 此项目基于原项目修改而来，原项目地址：[imsyy/home](https://github.com/imsyy/home)。在此对原作者表示感谢！本项目的修改仅用于个人学习与使用，若有侵权请联系删除。

<p>
<strong><h2>我的主页</h2></strong>
一个简单的个人主页，基于原项目进行了修改和优化。
</p>

![我的主页](/screenshots/main.jpg)

### 👀 Demo

> 由于 CDN 缓存原因，查看最新效果可能需要 `Ctrl` + `F5` 强制刷新浏览器缓存

- [我的主页](https://example.com)
- [我的主页 - Dev](https://dev.example.com)
- [我的主页 - 备用线路](https://backup.example.com)

### 🎉 功能

- [x] 载入动画
- [x] 站点简介
- [x] Hitokoto 一言
- [x] 日期及时间
- [x] 实时天气
- [x] 时光进度条
- [x] 音乐播放器
- [x] 移动端适配

### ⚙️ 部署方式

#### 手动部署

- **安装** [node.js](https://nodejs.org/zh-cn/) **环境**

  > node > 16.16.0  
  > npm > 8.15.0

- 然后以 **管理员权限** 运行 `cmd` 终端，并 `cd` 到 项目根目录
- 在 `终端` 中输入：

```bash
# 安装 pnpm
npm install -g pnpm

# 安装依赖
pnpm install

# 预览
pnpm dev

# 构建
pnpm build