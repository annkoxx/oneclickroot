### Root一键脚本

VPS应用环境：纯IPV4、纯IPV6、双栈IPV4+IPV6，可以在非root或root模式下运行。

集成获取最高权限属性（以防止被暴力破解后改属性）来创建或者更改ROOT密码

后续再次执行脚本意味着更改root密码！！

-----------------------------------------------------------------------------------------

一键脚本：

```
bash <(curl -sSL https://cdn.jsdelivr.net/gh/YG-tsj/oneclickroot/root.sh)
```

用户名：root，密码必须自定义。

设置成功后自动断开VPS，请更改原用户名为"root",并输入自定义密码进行VPS登录！

--------------------------------------------------------------------------------------

已测试支持甲骨文与谷歌云，理论上支持所有默认密钥型VPS。。

提示：密码不要设置得过于简单，容易被破解。如有密钥文件要保存好，以防万一！
