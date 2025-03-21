# pytdx
修改daily_bar_reader以读取科创板和北交所的日交易数据

pytdx version-1.7.2问题：
pytdx的原代码无法使用本地通达信金融终端中科创板和北交所的个股日交易数据。

解决方法：
先通过pip正常安装pytdx，然后更新python目录下..\Lib\site-packages\pytdx\reader中的daily_bar_reader.py

更新方法：
正常目录下的daily_bar_reader.py然后到上述目录覆盖原文件。

注意：
为避免异常，请将原daily_bar_reader.py文件保存在其它位置，如果发生意外，可恢复原文件。
