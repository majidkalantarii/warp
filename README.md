### Warp Insatll
```
bash <(wget -qO- https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh 2> /dev/null)
```
or
```
bash <(curl -Ls https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh)
```
### Warp Uninsatll
#### ```kill -15 $(pgrep warp-go) ```

#### 2、终止wgcf：```systemctl stop wg-quick@wgcf```


---------------------------------------------------------------------

### 二、多平台优选WARP对端IP + 无限生成WARP-Wireguard配置 一键脚本
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/endip.sh -o endip.sh && chmod +x endip.sh && ./endip.sh
```

Replit平台一键无限生成WARP-Wireguard配置：https://replit.com/@ygkkkk/WARP-Wireguard-Register

Replit平台一键无限生成WARP+密钥（2000多万GB流量）：https://replit.com/@ygkkkk/WarpKey-Register-PRO
