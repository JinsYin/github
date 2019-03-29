# Github Pages

利用 Github Pages 提供的网站功能，每个 Github 账号和组织可以创建 **一个** 网站，以及 **无数个** 项目网站。

## 个人或组织站点（限一个）

**1**. 创建一个名为 `username.github.io` 的代码仓库（`username` 必须是自己的用户名或组织名）

**2**. 克隆代码仓库

```bash
$ git clone https://github.com/username/username.github.io
```

**3**. Hello World

```bash
$ cd username.github.io
$ echo "Hello, world" > index.html
```

**4**. Push 到 Github

```bash
$ git add --all
$ git commit -m "试一试 Github Pages"
$ git push -u origin master
```

**5**. 浏览器访问 <https://username.github.io>

## 项目站点（无数个）

### 设置网站源

主分支作为源：

1. 在项目根目录创建 `index.html` 文件并添加一些内容
2. 到项目页面中点击 `Settings` 选项并滚动到 `GitHub Pages` 区域，选择 `master branch` 作为源
3. 浏览器访问 <http://username.github.io/my-project>

子目录作为源：

1. 在项目子目录 **/docs** 下创建 `index.html` 文件并添加一些内容
2. 到项目页面中点击 `Settings` 选项并滚动到 `GitHub Pages` 区域，选择 `master branch /docs folder` 作为源
3. 浏览器访问 <http://username.github.io/my-project>

### 选择主题

### 定制域名

## 参考

* [Github Pages](https://pages.github.com/)
