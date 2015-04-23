#Python traditional and simplified chinese translation library.

# Introduction #

  * Jianfan is a library for translation between traditional and simplified chinese.
  * two functions are provided by the library:
  * jtof: translate simplified chinese to traditional chinese
  * jtoj: translate traditional chinese to simplified chinese
  * the two functions accept one parameter that is unicode or string
  * the type of return value is unicode

  * Jianfan是一个简体中文和繁体中文转换的库。提供了两个函数：
  * jtof: 简体转换为繁体
  * ftoj: 繁体转换为简体
  * 函数接受unicode和string类型作为参数，返回值统一为unicode


# Details #

Add your content here.  Format your content with:
  * **Jianfan** is a **_python_** library for translation between traditional and simplified chinese
  * Easy to use, Light weight
  * https://python-jianfan.googlecode.com/hg/

# Usage #

  * Translate simplified chinese to traditional chinese.
  * >>> from jianfan import jtof
  * >>> s = u'中华'
  * >>> print jtof(s)
  * 中華

  * Translate traditional chinese to simplified chinese.
  * >>> from jianfan import ftoj
  * >>> t = u'中華'
  * >>> print ftoj(t)
  * 中华