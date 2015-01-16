# GitHub
GitHub使用心得

簡單操作過程

1.第一次初始
在Github開Repository
git clone [clone URL] 先把code從Github抓下來

2.
進到該目錄中
git branch [branch-name] 生一個新branch
git checkout [branch-name] 切換到此branch上

3.
git status 看修改了哪些檔案
git add [修改到的檔案] 一個檔一個檔自己加，因為這樣可以Double check自己到底改了哪些檔
git commit 註解要寫清楚 完成一個小功能就要commit一次
重複步驟3.直到 git status 顯示沒有任何修改過的檔案

4.
git checkout master
git merge [branch-name] 和master merge起來
git push 然後接著輸入Github的帳號密碼

如果只有一人work，每次的流程就是跑 2.~4.


備註：

加已有資料夾
1.開一個 GitHub Repository，取名與原資料夾同
2.將原資料夾先改名，再建立同名資料夾(空資料夾)
3.將前兩步驟連結
4.將原資料丟進去
