---
description: jq
---

# 解析json的工具

一、安装环境

```bash
sudo apt-get install jq 
```

二、获取参数

```bash
jq -r .TravelEndTime
# -r选项来确保从JSON中提取的值是原始的, 即去除了引号
```

