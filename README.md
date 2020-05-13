# pycnblog
博客园上传markdown文件 https://www.cnblogs.com/df888/p/11826480.html

# 环境

python3

# 配置

在config.py中，填写博客配置信息。

```python
blog_url = 'https://rpc.cnblogs.com/metaweblog/testblog'
blog_id = 'testblog'
username = 'zhangsan'
password = '123456'
```

## blog_url

blog_url在博客后台>设置，页面最下方的MetaWeblog访问地址。
https://rpc.cnblogs.com/metaweblog/testblog

## blog_id

blog_id就是访问地址的尾巴。
testblog

## username

username是登录用户名，跟blog_id不是同一个。

## password

password是密码。

# 运行

Windows cmd：

打开`cnblog_markdown.cmd`，提示`Please input file path:`<br/>
把文件往里一拖就完事了
