# mySublimeText3
我的SublimeText3插件和配置

使用方法:

   打开Sublime选择首选项，浏览程序包，在资源管理器中打开文件夹，关掉Sublime，删除该文件下所有文件，用Git将代码Clone到这里，然后打开Sublime


目前安装的插件:

10.27

+ GitGutter:Git显示、
+ HTML-CSS-JS Prettify:前端美化
+ ConvertToUTF8:文件转化
+ SublimeREPL:各种动态语言，交互终端
+ Alignment:智能化对齐
+ AutoPEP8 :格式化Python代码
+ BracketHighlighter:括号高亮
+ jQuery Jquery:提示
+ Color​Picker:调色板
+ ChineseLocalization:中文菜单栏，汉化（帮助栏目可以选择语言）
+ Autoprefixer:CSS前缀
+ DocBlockr:优雅生成文档
+ Emmet:前端生成HTML神器（会安装上PyV8）
+ HTML5:忽略
+ IMESupport :中文输入框，更随
+ TrailingSpaces:去掉尾巴上空格
+ Theme-Spacegray:唯美主题
+ SideBarEnhancements :增强侧边栏，可以出现在资源管理器中打开等等
+ SublimeCodeIntel :完全自动补全引擎

10.29

+ Markdown Preview:Markdown 浏览器中预览
+ MarkdownEditing：Markdown语法提示
+ SublimeLinter:多语言语法校验
+ Colorsublime:快速选择多种主题

已知问题：
Sublime自带的Markdown插件和Markdown Editing、Markdown Lighting冲突

若发现Markdown插件不正常，请先停用Markdown，然后启用其他组件，最好再重启一下编辑器


停用工具包，使用时，请手动开启


`    "Colorsublime",
    "ColorPicker",
    "DocBlockr",
    "Emmet",
    "Markdown",
    "SideBarEnhancements",
    "SublimeCodeIntel",
    "SublimeLinter",
    "Vintage"`


==========================


Sublime Text PackageControl插件总是安装不成功？？!

1.请在自己的host中添加

`
    50.116.34.243 sublime.wbond.net,
`

`
    192.30.252.97 nodeload.github.com
`



2.自行开启代理，并且在Sublime用户配置文件中添加代理设置：

`
    "http_proxy": "http://your_proxy_here:port",
`

`
    "https_proxy": "http://your_proxy_here:port",
`

注意:https_proxy 后面跟着的是 http，Sublime目前不支持https的代理



3.个人配置

`   "color_scheme": "Packages/Theme - Spacegray/base16-ocean.dark.tmTheme",//主题
    "debug": true,//Sublime Debug开关，可以用来看后台报错
    "draw_white_space": "all",//空格缩进，显示
    "font_face": "Consolas",//字体
    "font_size": 14,//字体尺寸
    "http_proxy": "http://127.0.0.1:1080",//HTTP代理
    "https_proxy": "http://127.0.0.1:1080",//HTTPs代理
    "ignored_packages"://关闭插件的集合，用的时候再开启，增强Sublime的稳定性与速度
    [
        "ColorPicker",
        "Colorsublime",
        "DocBlockr",
        "Emmet",
        "MarkdownEditing",
        "SideBarEnhancements",
        "SublimeCodeIntel",
        "SublimeLinter",
        "Vintage"
    ],
    "tab_size": 4,//定义缩进为4个空格
    "theme": "Spacegray.sublime-theme",//自定义主题
    "translate_tabs_to_spaces": true,//Tab转为空格
    "trim_trailing_white_space_on_save": true,//保存时，自动去掉末尾空格，处女座福音
    "save_on_focus_lost": true,//Sublime失去鼠标焦点，自动保存
    "bold_folder_labels": true//文件目录字体加粗，容易分辨`