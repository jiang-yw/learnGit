## Git 学习笔记(2)

### 版本回退
- 命令 `git log` 列出历史提交记录

    1. 参数 `--online` 查看历史记录简洁版本

- 命令 `git reflog` 查看命令历史（commit、reset等操作）

- 命令 `git reset --hard HEAD^` 回退到上一个版本

    1. HEAD 指当前版本 
    2. HEAD^^ 回退到上上个版本
    3. HEAD~100 往上100个版本
    4. HEAD^ 位置可修改为 commit id ，可以用来回退到回退前的版本
