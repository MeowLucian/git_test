# git_test
git function test

## 基礎設定

* 查詢版本
```
git version
```

* 查詢設定列表
```
git config --list
```

* 輸入姓名
```
git config --global user.name "你的名字"
```

* 輸入email
```
git config --global user.email "你的email"
```

## 新增本地/遠端數據庫

* 在本地資料夾新增數據庫
```
git init
```

* 複製遠端數據庫
```
git clone 遠端數據庫網址
```

## 增加/刪除檔案

* 增加檔案進入索引
```
git add 檔案名稱
```

* 增加全部檔案進入索引
```
git add .
```

* 查詢狀態
```
git status
```

* 顯示歷史紀錄
```
git log
```

* 將索引提交到數據庫
```
git commit -m '更新訊息'
```

## 還原指令
* 還原工作目錄與索引，會跟最後一次 commit 保持一樣
```
git reset --hard
```

* 全部檔案取消索引
```
git reset HEAD
```

* 單一檔案取消索引
```
git reset HEAD 檔案名稱
```

* 恢復單一檔案到最新 commit 狀態
```
git checkout 檔案名稱
```

* 刪除最近一次 commit 
```
git reset --hard "HEAD^"
```

* commit 後發現有幾個檔案忘了加入進去，想要補內容進去時
```
git commit --amend
```

## 分支

* 顯示所有本地分支
```
git branch
```

* 新增分支
```
git bracnch 分支名稱
```

* 切換分支
```
git checkout 分支名稱
```

* 合併指定分支到目前的分支
```
git merge 分支名稱
```

* 刪除分支
```
git branch -d 分支名稱
```

## 遠端數據庫操作

* 複製遠端數據庫
```
git clone 遠端數據庫網址
```

* 查詢遠端數據庫
```
git remote
```

* 將本地分支推送到遠端分支
```
git push 遠端數據庫名稱 遠端分支名稱
```

* 將遠端分支拉下來與本地分支進行合併
```
git pull
```

## 標籤

* 查詢標籤
```
git tag
```

* 查詢詳細標籤
```
git tag n
```

* 刪除標籤
```
git tag -d 標籤名稱
```
