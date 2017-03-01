#mobile-util
一个精致的移动端前端开发帮助库。提供非常精简的移动端兼容性方案实现：
- 类jQuery选择器Util(".class")
- 为dom元素提供tap（已处理点透）、show事件（已节流处理）
  Util("#id").on("tap",callback),Util("#id").on("show",callback)
- 提供html文档就绪事件Util.ready(callback)
- 提供类jQuery的ajax请求方法Util.ajax(options)
- 获取url参数Util.getUrlParam("key")
- 获取移动端系统环境信息Util.osType()
- 携带url参数的页面跳转Util.redirectWithUrlParam()