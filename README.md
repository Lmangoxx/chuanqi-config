### 改完配置后立即让所有用户生效

jsDelivr 默认缓存约 12 小时。`git push` 之后跑一次 purge 命令主动刷 CDN，几秒内全球生效：

```bash
curl https://purge.jsdelivr.net/gh/Lmangoxx/chuanqi-config@main/chuanqi.json
```
