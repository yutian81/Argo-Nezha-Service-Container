## 官方一键安装

```bash
curl -L https://raw.githubusercontent.com/nezhahq/scripts/refs/heads/main/install.sh -o nezha.sh && chmod +x nezha.sh && sudo ./nezha.sh
```

> 通信域名使用非cdn域名，若未为该域名申请证书，TLS 请选择 N

## 开启 github 验证

将 `config.yml` 中的内容留空的部分的填写完整，复制到 vps 的 `/opt/nezha/dashboard/data/config.yaml` 文件中保存

运行以下命令重启 docker

```bash
docker restart nezha-dashboard
```

## 前端自定义代码--个性化页眉页脚
