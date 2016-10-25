#### git command
git rm a.txt ，误将a.txt删除后找回方法：

1. git log 找到离没删文件前最近的commit id
2. 将操作过的其它文件转移
3. git reset --hard "commit id"