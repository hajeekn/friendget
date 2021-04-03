---
name: Friends chain application template
about: Moved here from Gitee
title: "[Please wait]"
labels: Friends chain waiting for review
assignees: ladjeek-actions

---

**标题请书写你的链接，不要写其他内容**
**Tag如果留空则审核后默认在Gitee友链内**
​

```yaml
# 显示名称
name: 你的名称

# 跳转地址
link: 你的链接

# 你的头像
avatar: 你的头像

# 你的描述
descr: 你的描述

# 边框及鼠标悬停的背景颜色，允许设置渐变色
--primary-color: #49b1f5

# 边框大小
border-width: 0px

# 边框样式
border-style: solid

# 鼠标悬停头像旋转角度
--primary-rotate: 0deg

# 边框动画 参考 https://developer.mozilla.org/zh-CN/docs/Web/CSS/animation
# 内置动画：borderFlash（边框闪现）、link_custom1(跑马灯)、link_custom(主颜色呼吸灯)
animation: borderFlash 0s infinite alternate

# 头像动画 参考 https://developer.mozilla.org/zh-CN/docs/Web/CSS/animation
# 内置动画：auto_rotate_left（左旋转）、auto_rotate_right（右旋转）
img_animation: auto_rotate_right 0s linear infinite

# 标签
tag: 

# 风格 可选项 item和card
card_style: item
# 自定义网站截图（当样式为card时可以自定义网站截图，防止api接口宕掉无法显示图）
screenshot: 

## 站点截图
当使用card类型的卡片时会使用到网站的截图，如果配置字段screenshot未填写，则默认调用https://image.thum.io/get/width/1024/crop/768/你的网址，进行填充。如果填写，则使用用户填写的值作为屏幕截图。
为了便于用户截图可以使用此接口进行截图后，将图片保存然后上传到图床然后填写。

```
