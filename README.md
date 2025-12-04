## sing-box VLESS+REALITY脚本

### 教程
`config.json` - 服务端配置
`config.yaml` - 客户端配置
按提示改即可

### sing-box 指令
```bash
# sing-box 指令

# Windows 运行 singbox
.\sing-box.exe run -c config.json

# 检查配置文件
sing-box check

# 检查状态
systemctl status sing-box

systemctl restart sing-box

# 查看日志
journalctl -u sing-box -f
```

