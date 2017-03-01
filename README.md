#mobile-util
一个精致的移动端前端开发帮助库。提供非常精简的移动端兼容性方案实现：
- 类jQuery选择器@(".class")
- 为dom元素提供tap（已处理点透）、show事件（已节流处理）
  @("#id").on("tap",callback),@("#id").on("show",callback)
- 提供html文档就绪事件@.ready(callback)
- 提供类jQuery的ajax请求方法@.ajax(options)
- 获取url参数@.getUrlParam("key")
- 获取移动端系统环境信息@.osType()
- 携带url参数的页面跳转@.redirectWithUrlParam()