# 生成Lua模版

在绑定类型到Lua后，可以通过 `UnLua工具栏 -> 创建Lua模版文件` 来快速在绑定的路径下生成对应的Lua文件。

默认会根据类型名称在 `UnLua/Config/LuaTemplates` 目录下来查找模版文件，如果文件不存在会使用它的父类名称来继续查找。

## 自定义

可以根据自己的需要，在 `工程目录/Config/LuaTemplates` 目录下创建模版文件，生成的时候会优先使用。

注意文件编码需要为UTF-8(No BOM)。