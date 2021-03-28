开发准备工作：
1. 打开翻墙。
2. 找一个安全的目录，运行 
3. 安装 [git](https://git-scm.com/downloads) 和 [Ruby](https://rubyinstaller.org/downloads/) (选择 `Ruby+Devkit 3.0`).
4. 找一个安全的目录，在地址栏输入 `cmd` 然后回车。运行：
    1. `git clone git@github.com:xupefei/pooi.moe.git`
    2. `gem install jekyll bundler`
    3. `bundle install`
    4. `bundle exec jekyll serve`
5. 在浏览器打开 `http://127.0.0.1:4000` 预览网站。

开发过程：
1. 添加一个新 git 分支：`git checkout -b 分支名`，`分支名`可以为任何英文字母组合。
2. 修改任意文件。
3. 运行 `bundle exec jekyll serve` 打开 `http://127.0.0.1:4000` 预览修改。按下 <kbd>CTRL</kbd> + <kbd>C</kbd>停止预览。
4. 重复步骤 2 和 3。

修改完成后：
1. 提交修改：在命令行运行
    1. `git add .`
    1. `git push origin`
2. 打开 `https://github.com/xupefei/pooi.moe`，此页会出现一个黄色横幅。点击横幅中的 `Create a pull-request`。
3. 点击绿色按钮确认创建PR。
4. 在群里提醒 @Paddy 盖章。
