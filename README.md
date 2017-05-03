# pedis

在做数据处理时，需要保存一些中间数据，经常使用Redis和Pickle。

* Redis功能强大，有丰富的API，但需要安装服务，不方便分享。
* Pickle方便分享，但操作不方便。

于是就想写一个工具，用使用Redis的方式来操作Pickle，故名pedis。
