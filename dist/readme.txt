在cmd下载运行

feed2mobi.exe -url=url 或 feed2mobi.exe url

如：

feed2mobi.exe -url=http://www.cnbeta.com/backend.php
feed2mobi.exe -url=http://cn.engadget.com/rss.xml


如果要抓取全文只需提供正文所在xpath即可

如：

feed2mobi.exe -url=http://www.cnbeta.com/backend.php -xpath="//div[@id='news_content']"