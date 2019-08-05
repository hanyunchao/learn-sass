# sass编译命令
> 最简单的编译 `sass file.scss file.css` 
# sass编译支持中文
>路径:C:\Ruby23-x64\lib\ruby\gems\2.3.0\gems\sass-3.4.25\lib\sass => engine.rb  
>在require() 后面添加  
>```Encoding.default_external = Encoding.find('utf-8')```

# sass编译输出的四种格式
- nested（嵌套）
- compact（紧凑）
- expanded（扩展）
- compressed（压缩）
> 若要修改默认输出的编译格式可在C:\Ruby23-x64\lib\ruby\gems\2.3.0\gems\sass-3.4.25\lib\sass => engine.rb  
> 修改下面代码块中的style
```
    DEFAULT_OPTIONS = {
      :style => :expanded,
      :load_paths => [],
      :cache => true,
      :cache_location => './.sass-cache',
      :syntax => :sass,
      :filesystem_importer => Sass::Importers::Filesystem
    }.freeze
```
