# git commit 提交规范

### commit message格式
` <type>(<scope>): <subject> `

包括三个字段：type（必需）、scope（可选）和subject（必需）。

### （1）type

type用于说明 commit 的类别，只允许使用下面标识：

feat：新功能（feature）

fix：修补bug

style： 不影响代码含义的更改 (例如空格、格式化、少了分号)

perf：优化相关，比如提升性能、体验

docs：文档（documentation）

refactor：重构（即不是新增功能，也不是修改bug的代码变动）

test：增加测试

chore：构建过程或辅助工具的变动

### （2）scope

scope用于说明 commit 影响的范围，比如数据层、控制层、视图层等等，视项目不同而不同。

### （3）subject

subject是 commit 目的的简短描述，不超过50个字符。

以动词开头，使用第一人称现在时，比如change，而不是changed或changes
第一个字母小写
结尾不加句号（.）
