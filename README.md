# lint-js
代码风格检查

针对每次提交到暂存区的代码进行代码风格检查

## 需要安装的依赖

### husky

添加 git 钩子

### lint-staged

对 Git 暂存区文件进行检查：

* linters：检查的目录
* ignore：忽略规则的目录

### eslint

使用eslint进行代码风格检查，暂时选择Airbnb的规范