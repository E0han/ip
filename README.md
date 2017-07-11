###Get IP proxy for python script

``` 
这个ip库可以直接调用，为python3爬虫提供ip代理功能，只包含一个函数get_proxy()，参数请设置为2-10之间的任意整数，获取的ip代理数量为参数-1.
用法:
`use_proxy=proxy.get_proxy(2)`
use_proxy是一个字典，将包含如下格式的代理格式:
`"http":"http://ip:port"`
建议使用requests库，可以在提交get或post请求时直接装备代理
```
###脚本更新日志log

```
此脚本会长期更新，以防实效
- first release date: 11/7/2017
```