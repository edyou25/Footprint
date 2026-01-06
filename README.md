# 我们的足迹 - 情侣足迹地图

一个展示你和女朋友一起走过的地方的网页。

## 使用方法

1. 直接在浏览器中打开 `index.html` 文件即可查看地图
2. 或者使用本地服务器运行（推荐）：

```bash
# 使用 Python 3
python3 -m http.server 8000

# 或使用 Node.js
npx http-server
```

然后在浏览器中访问 `http://localhost:8000`

## 功能特点

- 🗺️ 嵌入 Google My Maps，展示所有足迹地点
- 💕 精美的渐变背景和现代化设计
- 📱 响应式设计，支持手机和电脑访问
- ❤️ 温馨的标题和动画效果

## 自定义

如果你想修改地图，可以：

1. 在 Google My Maps 中编辑你的地图
2. 更新 `index.html` 中的地图 ID（mid 参数）
3. 修改标题、颜色等样式

## 重要：设置地图为公开访问

**⚠️ 如果其他人无法看到地图，需要将 Google My Maps 设置为公开：**

1. 打开你的 [Google My Maps](https://www.google.com/maps/d/edit?mid=1LUlaWSUHRk2Q5ZpKm6CipHDTpGYEtww&usp=sharing)
2. 点击右上角的 **"共享"** (Share) 按钮
3. 在"获取链接"部分，将访问权限改为：
   - **"知道链接的任何人"** (Anyone with the link) 或
   - **"公开在网络上"** (Public on the web)
4. 点击 **"完成"** (Done)
5. 刷新网页，地图应该可以正常显示了

### 为什么需要这样做？

- Google My Maps 默认是私有的，只有地图创建者登录后才能查看
- 设置为公开后，任何人都可以通过网页访问地图，无需登录 Google 账号
- 网页会自动检测地图是否可访问，并显示友好的提示信息

## 注意事项

- 确保你的 Google My Maps 设置为"公开"或"通过链接共享"，这样网页才能正常显示
- 如果地图无法显示，请检查地图的分享设置
- 网页会显示提示信息，指导如何设置地图为公开访问

