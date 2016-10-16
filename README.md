# Sass
the base useful for sass

SASS是一种CSS的开发工具，提供了许多便利的写法，大大节省了
设计者的时间，使得CSS的开发，变得简单和可维护

Sass是Ruby写的，所以需要安装Ruby，然后在安装Sass
http://rubyinstaller.org/downloads
https://rubygems.org/

安装sass
gem install sass

是否安装成功  
sass -v 出现版本号即代表安装成功

将sass转化为css的命令
sass test.scss(sass文件名):test.css(css文件名)
注意，sass文件的后缀名为.scss
watch 监听的用法
sass --watch test.scss:test.css
