# 💌 H5邀请函 - Vercel部署版

这是一个精美的H5邀请函，专为Vercel部署优化。

## 🎨 项目特色

- 📱 **移动端优化** - 完美适配手机屏幕
- 🎨 **现代化设计** - 渐变背景、卡片式布局
- ✨ **流畅动画** - 淡入效果、浮动装饰
- 🎯 **交互体验** - 确认参加按钮
- 🚀 **一键部署** - Vercel静态部署

## 🛠️ 技术栈

- HTML5 + CSS3
- 原生JavaScript
- 响应式设计
- Vercel静态部署

## 🚀 部署步骤

### 方法1：Vercel一键部署

1. **Fork这个项目到你的GitHub**
2. **访问 https://vercel.com**
3. **用谷歌账号登录**
4. **导入项目**
5. **点击Deploy**

### 方法2：手动部署

```bash
# 1. 克隆项目
git clone https://github.com/你的用户名/invitation-h5-vercel.git
cd invitation-h5-vercel

# 2. 安装依赖
npm install

# 3. 本地预览
npm run dev

# 4. 推送到GitHub
git add .
git commit -m "Deploy to Vercel"
git push
```

## 🎯 自定义内容

编辑 `public/index.html` 文件：

### 修改邀请函内容
```html
<!-- 修改标题 -->
<h1>💌 你的邀请函标题</h1>

<!-- 修改活动详情 -->
<div class="value">你的活动时间</div>
<div class="value">你的活动地点</div>
```

### 修改样式
在 `<style>` 标签中修改CSS：

```css
/* 修改主色调 */
background: linear-gradient(135deg, #你的颜色1, #你的颜色2);

/* 修改卡片颜色 */
background: linear-gradient(135deg, #你的颜色1, #你的颜色2);
```

## 📱 移动端适配

项目已完美适配移动端：
- 响应式布局
- 触摸友好的按钮
- 优化的字体大小
- 流畅的动画效果

## 🎨 自定义指南

### 更换背景颜色
```css
body {
    background: linear-gradient(135deg, #FF6B6B, #4ECDC4);
}
```

### 更换主色调
```css
.card-header {
    background: linear-gradient(135deg, #你的颜色1, #你的颜色2);
}

.rsvp-button {
    background: linear-gradient(135deg, #你的颜色1, #你的颜色2);
}
```

### 添加背景音乐
```html
<audio autoplay loop>
    <source src="你的音乐.mp3" type="audio/mpeg">
</audio>
```

## 🚀 部署后操作

1. **自定义域名**（可选）
   - 在Vercel项目设置中添加域名
   - 配置DNS记录

2. **分享链接**
   - 复制Vercel提供的URL
   - 分享到微信、QQ等平台

3. **统计分析**
   - 集成Google Analytics
   - 添加访问统计

## 📞 需要帮助？

如果在部署或使用过程中遇到问题，请提供：
1. 错误信息
2. 你的操作步骤
3. 期望的效果

我会帮你解决具体问题！

---

🎉 **祝你邀请函制作成功！** 🎉