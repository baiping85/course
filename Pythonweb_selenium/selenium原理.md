**Selenium 是什么？**

Selenium是ThoughtWorks员工在业余时间开发并维护的开源项目，并且在ThoughtWorks的项目中被广泛应用。简单地说，Selenium是一个自动化的web应用功能测试工具。

**Selenium 原理**
![avatar](/home/picture/1.png)


**selenium环境搭建**


Client：　
pycharm　python3.6

Driver：　
Chrome     → ChromeDriver　
Firefox    → FirefoxDriver　
IE         → InternetExplorerDriverSelenium


**Selenium安装**

pip install selenium

```
from selenium import webdriver  # 导入
driver = webdriver.Chrome()  # 启动谷歌浏览器
driver.get("http://www.baidu.com")  # 打开百度网址
```


使用脚本启动不同浏览器启动浏览器前需配置好浏览器对应driver：
Chrome --chromedriver.exe ：谷歌浏览器调试驱动插件Firefox --geckodrive.exe ： 火狐浏览器调试驱动插件IE --MicrosoftWebDriver.exe ： IE浏览器调试驱动插件将上面三个exe文件下载后放置到python目录下


<font color=red>注意：启动谷歌浏览器前需要配置好谷歌浏览器中间件 ，从网上下载chromedriver.exe ，将其放置到python的安装目录下<fontt>
