# 常用命令和资料
### 领水网址
[vana fauce](https://faucet.vana.org/)

### 教程
[Guild](https://service.josephtran.xyz/testnet/vana/dlp-validator/)

#用PM2启动
```
cd ~
cd vana-dlp-chatgpt
pm2 start "poetry run python -m chatgpt.nodes.validator" --name validator
```
