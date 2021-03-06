搜索引擎利用
========================================
恰当地使用搜索引擎（Google/Bing/Yahoo/Baidu等）可以获取目标站点的较多信息。

搜索引擎处理流程
--------------------------------
- 数据预处理
    - 长度截断
    - 大小写转化
    - 去标点符号
    - 简繁转换
    - 数字归一化，中文数字、阿拉伯数字、罗马字
    - 同义词改写
    - 拼音改写
- 处理
    - 分词
    - 关键词抽取
    - 非法信息过滤

搜索技巧
----------------------------------------
- site:www.hao123.com
    - 返回此目标站点被搜索引擎抓取收录的所有内容
- site:www.hao123.com keyword
    - 返回此目标站点被搜索引擎抓取收录的包含此关键词的所有页面
    - 此处可以将关键词设定为网站后台，管理后台，密码修改，密码找回等
- site:www.hao123.com inurl:admin.php
    - 返回目标站点的地址中包含admin.php的所有页面，可以使用admin.php/manage.php或者其他关键词来寻找关键功能页面
- link:www.hao123.com
    - 返回所有包含目标站点链接的页面，其中包括其开发人员的个人博客，开发日志，或者开放这个站点的第三方公司，合作伙伴等
- related:www.hao123.com
    - 返回所有与目标站点”相似”的页面，可能会包含一些通用程序的信息等
- intitle:"500 Internal Server Error" "server at"
    - 搜索出错的页面
- inurl:"nph-proxy.cgi" "Start browsing"
    - 查找代理服务器

除了以上的关键字，还有allintile、allinurl、allintext、inanchor、cache等。

快照
----------------------------------------
搜索引擎的快照中也常包含一些关键信息，如程序报错信息可以会泄漏网站具体路径，或者一些快照中会保存一些测试用的测试信息，比如说某个网站在开发了后台功能模块的时候，还没给所有页面增加权限鉴别，此时被搜索引擎抓取了快照，即使后来网站增加了权限鉴别，但搜索引擎的快照中仍会保留这些信息。

另外也有专门的站点快照提供快照功能，如 Wayback Machine 和 `Archive.org <https://archive.org/>`_ 等。

Github搜索技巧
----------------------------------------
- ``@example.com password/pass/pwd/secret/credentials/token``
- ``@example.com username/user/key/login/ftp/``
- ``@example.com config/ftp/smtp/pop``
- ``@example.com security_credentials/connetionstring``
- ``@example.com JDBC/ssh2_auth_password/send_keys``

tips
----------------------------------------
- 查询不区分大小写
- ``*`` 代表某一个单词
- 默认用and
- OR 或者 | 代表逻辑或
- 单词前跟+表强制查询
- 引号引起来可以防止常见词被忽略
- 括号会被忽略
