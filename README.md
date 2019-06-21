# Flask
hello git


### git
- git init
    - 在本地自己创建一个仓库 
- git clone xxx
    - 从指定位置获取克隆已有仓库
    
### git操作
- git pull
    - 从远端服务器拉取代码文件
- git push
    - 将本地代码文件推送到服务器
    
- git add
    - 添加版本追踪
    - 添加文件变更标记  
- git commit
    - 将变更提交到本地仓库
- git status
    - 查看工作空间状态
- .gitignore
    - git忽略规则
    - 写入.gitignore文件中的文件或目录，git将不会进行版本跟踪
    
#### 指令操作
- git status    
    - 查看工作空间状态
    - 如果存在红色或绿色文件，代表还有代码文件没有提交
    - 需要进行追踪，git add
- git add
    - 添加文件到版本控制中去
    - git add filename
    - git add -A/--all 添加所有变更文件
- git commit
    - 提交文件到本地仓库
    - 记得写提交日志 git commit -m '修改描述'
- git push
    - 推送代码文件到远端服务器对应的分支
    - git push origin master
    
- git log 退出指令 按q
    - 代码提交日志
    
- 创建分支
    - git branch
        - git branch 'BRANCH_NAME'
        - 创建一个新的分支但没有切换
    - git checkout
        - git checkout -b 'BRANCH_NAME'
        - 创建并切换到指定分支上
        - git checkout branch_name
        - 切换到指定分支上
