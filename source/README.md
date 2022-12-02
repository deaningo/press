# hexo press theme blog

## 安装

模板使用`ejs + less`，安装依赖

```
npm install hexo-renderer-ejs --save
npm install hexo-renderer-less --save
```

## 配置

配置根目录`_config.yml`

- 切换主题 `theme: press`
- 设置中文 `language: zh-CN`
- 代码高亮
  ```yml
  highlight:
    hljs: true #新增项
  ```

配置主题项：

- 具体参考 `theme/press/_config.yml`
