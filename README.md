本仓库是用来保存未发布博客的草稿。



## Preparation
### nvm

用于node的版本管理。

安装
```bash
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
```

zshrc已配置好。

使用版本为：12.14.1

### npm

Install nodejs.



### hexo

```bash
sudo npm install hexo-cli -g
```

> `-g`: install globally

### hexo-deployer-git

```bash
sudo npm install hexo-deployer-git -g
```


###  node_modules

If `package.json` exists:

```bash
npm install
```

> My `package.json` exists.

### Package

abbrlink

```bash
npm install hexo-abbrlink --save
```

### themes

1. You need to create `themes` folder.
2. `git clone` your theme. (links are below)
3. the modified `_config.yml` files are stored in `/source/_data/`
    - copy **necessary files** (e.g. `Chic.yml`) to the right position of related theme folder (e.g. `/themes/Chic`)

**Notes**

> The filename of chosen theme folder must be kept same with the theme's name written in `/_config.yml`. (If not kept same, layout will be lost.)



## 关于

## 主题选择

### 简洁

1.apollo

```bash
npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
```

2.polarbear

```bash
npm install hexo-renderer-scss --save

git clone https://github.com/frostfan/hexo-theme-polarbear themes/polarbear
```

3.Maupassant

[Document](https://www.haomwei.com/technology/maupassant-hexo.html)

4.**Chic**

```bash
git clone https://github.com/Siricee/hexo-theme-Chic.git
```

### 漂亮 & 复杂

icarus
