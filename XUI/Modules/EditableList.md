### EditableList 可编辑列表

此组件在界面上显示一个子菜单项, 用于链接一个可编辑的字符串列表. 

|   键   |   类型   |   描述   |   条件   |
|--------|----------|----------|----------|
|footerText|字符串|显示在列表选项下方的小字|可选, 可本地化|
|maxCount|整数|最多选择项目数|\-|

|  主题键  |  描述  |
|----------|--------|
|textColor|颜色|文字颜色|
|caretColor|颜色|光标颜色|
|placeholderColor|颜色|占位符颜色|

|   返回类型   |   描述   |
|--------------|----------|
|包含字符串的数组|列表内容|

```lua
{
    maxCount = 10;
    defaults = "com.yourcompany.yourscript";
    cell = "EditableList";
    label = "Editable List";
    key = "list-4";
    default = {
        "Default";
    };
};
```

![QQ20171016-180741.png-157.3kB](EditableList/QQ20171016-180741.png)
