### 创建模块
```bash
docker exec -it -uroot odoo odoo scaffold book_store /mnt/extra-addons
```

### 重启odoo服务
```bash
docker compose restart odoo
```

### 查看日志
```bash
docker logs --tail 100 -f odoo

```
# 设置代理
```bash
git config --global https.proxy http://127.0.0.1:7890
git config --global https.proxy https://127.0.0.1:7890
```

# 取消代理
````bash
git config --global --unset http.proxy
git config --global --unset https.proxy
```