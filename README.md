# 京东副业 PCS - 每日优惠精选

每天早上 8:30 自动更新京东优惠商品，手机浏览器打开即可查看。

👉 **[打开页面](https://tigerzhang.github.io/jd-pcs/)**

## 项目结构

```
├── docs/          # GitHub Pages 发布目录
├── scripts/       # Python 脚本
├── config.json    # 配置文件
└── .gitignore
```

## 使用说明

1. 每天打开 https://tigerzhang.github.io/jd-pcs/
2. 看到当天10条优惠商品
3. 点击"复制链接"按钮
4. 粘贴到微信群分享

## 技术栈

- 数据源：京东联盟 API
- 后端：Python 3
- 部署：GitHub Pages
- 定时：macOS crontab
