## Git 学习笔记(1)

> repository 版本库

### 创建仓库
- 命令 `` git init`` 在所在目录创建仓库（.git 目录）

### 基本操作
- 命令 `git add` 将文件添加到缓存（stage）
        1. 添加多个文件 `git add <file 1>...<file n> `

- 命令 `git commit` 将缓存区文件提交到仓库
        2. 参数 `-m` 本次提交说明（未设置尝试打开编辑器，默认为 vim）

- 命令 `git status` 查看提交后是否有修改
        3. 参数 `-s` 简短结果输出

- 命令 `git diff` 查看执行 `git status` 结果详细信息
        1. 尚未缓存的改动 `git diff` 
        2. 已缓存的改动  `git diff --cached`
        3. 查看已缓存和未缓存的所有改动 `git diff HEAD`
        4. 显示摘要而非整个 diff `git diff --stat`
        