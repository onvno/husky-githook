# Husky-Githook

处理项目合并分支时，容易遗忘`npm install`

#### 使用说明及注意事项
* `git merge`成功合并后会自动执行`install`操作
* `git merge`时如遇到冲突，没办法自动触发`install`

#### TODO
* `npm install`如报错如何处理?