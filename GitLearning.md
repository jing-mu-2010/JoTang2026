# git操作
1. git add .暂存
2. git commit -m "first commit"提交至本地仓库
3. git remote add origin https://github.com/jing-mu-2010/JoTang2026.git关联仓库
4. git push -u origin main
5. git push -u origin main -f（-f 强制推送）
## git克隆以及修改push
1. git clone <仓库地址>
2. cd <项目文件夹名称>
3. git checkout -b feature-xxx（创建新分支并切换至该分支）
4. git status（查看当前状态）
5. git add .
6. git commit -m "写明修改内容"（修改信息）
7. git pull origin <当前的分支名>
8. git push -u origin <当前的分支名>
9. git push（非第一次推送，只需简单执行）

