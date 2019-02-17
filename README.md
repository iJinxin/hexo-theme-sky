[线上地址](https://ijinxin.github.io/)
## 功能简介
hexo-theme-sky 是一款简洁轻量的 hexo 博客主题，主要包含以下功能：
- 语言切换，目前支持中文和英文
- 文章访问统计
- 文章目录
- 评论功能，目前使用的是gitment
- 代码高亮

## 使用指南
安装 ``` hexo ```
```
npm install hexo-cli -g
hexo init blog
```
下载 ``` hexo-theme-sky ```主题
```
cd blog
git clone https://github.com/iJinxin/hexo-theme-sky themes/sky
```
修改博客根目录下的配置文件 ```_config.yml``` , 启用 ``` sky ``` 主题
```
theme: sky
```
安装依赖项
```
npm install
npm install hexo-renderer-scss --save
```
运行
```
hexo server
```
启动服务后，访问 http://localhost:4000 预览主题

更多主题配置 [document](https://ijinxin.github.io/blog/2018/10/29/hexo-theme-sky%E6%8C%87%E5%8D%97/)

## 说明
<blockquote>
如果对您有帮助，可以点击右上角“Star”支持一下，谢谢！

或者您有更好的想法，更棒的建议，也可以提issue，我会考虑实现
<blockquote>

