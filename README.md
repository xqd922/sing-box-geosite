# sing-box-rule-set-transform
# 自动转换其它规则集为sing-box格式规则集

在links.txt添加规则集，触发actions，自动转化为sing-box格式，储存于Rule文件夹中。
需生成token填写到仓库设置里，让GitHub Actions有权限修改你的仓库

规则集源文件写法eg:

```json
{
  "tag": "geosite-wechat",
  "type": "remote",
  "format": "source",
  "url": "https://raw.githubusercontent.com/Toperlock/sing-box-geosite/main/wechat.json",
  "download_detour": "auto"
}
```



# 致谢（排名不分先后）
[@Toperlock](https://github.com/Toperlock)

[@izumiChan16](https://github.com/izumiChan16)

[@ifaintad](https://github.com/ifaintad)

[@NobyDa](https://github.com/NobyDa)

[@blackmatrix7](https://github.com/blackmatrix7)

[@DivineEngine](https://github.com/DivineEngine)
