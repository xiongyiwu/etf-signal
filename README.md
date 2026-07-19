# ETF信号监控

每天14:35自动更新ETF信号，打开浏览器即可查看。

## 部署步骤

1. 在GitHub创建仓库 `etf-signal`
2. 将本文件夹内容推送到仓库
3. 仓库 Settings → Pages → 选 GitHub Actions 部署
4. 打开 `https://你的用户名.github.io/etf-signal/` 查看

## 监控标的
- 589720 科创创新药ETF
- 159611 广发电力ETF
- 588170 科创半导体ETF
- 515050 通信ETF

## 规则
120分钟MA5/MA60定方向 + 5分钟MA5/MA60交叉
