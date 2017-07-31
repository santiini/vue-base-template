# vue-base-template
A template with vue for simple projects

## 模版文件

### meta.js: 该文件必须导出为一个对象, 用于定义模板的 meta 信息, 对于 meta.{js,json} 文件, 目前可定义的字段如下:

1. prompts<Object>: 收集用户自定义数据

2. filters<Object>: 根据条件过滤文件

3. completeMessage<String>: 模板渲染完成后给予的提示信息, 支持 handlebars 的 mustaches 表达式

4. complete<Function>: 模板渲染完成后的回调函数, 优先于 completeMessage

5. helpers<Object>: 自定义的 Handlebars 辅助函数



### 模板仓库的根目录下必须有 template 目录, 在该目录下定义你的模板文件
