git 仓库基本概念：           
git add 提交工作区代码到暂存区          
git commit -m"xxx"给暂存区加注释      
git push 远程主机名 本地分支名:远程分支名 从暂存区提交代码到仓库                 




git 撤销某次操作

亲测   git revert commit_id   不好使        
使用   git checkout HEAD~2 文件名搞定；          
估计   git revert HEAD~2 文件名也能搞定；          

git 删除文件
git rm xxx  删除库文件        
git rm --cached xxx  只删除缓存    


git 提交                        
git push 远程主机名 本地分支名:远程分支名           
git push origin HED:refs/for/xxx             
git remote 查看远程主机名            
