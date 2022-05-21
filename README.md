# git-demo
- 測試git指令

> 建立時間
- 2022/5/21
- 作者:
    - 陳岳洋(Jerry)



> git reset

- git reset --hard commit-object
	- 名義上後面新增/修改的檔案都會被刪除
- git reset --mixed commit-object
	-　A->U
- git reset --soft commit-object
	- 恢復在暫存區

- git reflog
	- git reset (checkout) commit-object

>表格  

| 專案        | 價格   |  數量  |
| --------   | -----:  | :----:  |
| 計算機      | $1600   |   5     |
| 手機        |   $12   |   12   |
| 管線        |    $1    |  234  |

>github  
https://www.mdeditor.tw/  

git init  
git add README.md  
git commit -m "first commit"  
git branch -M master  
git remote add origin https://github.com/17app001/git-demo2.git  
git push -u origin master  