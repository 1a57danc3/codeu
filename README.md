這個是一個運行在SAE（Sina App Engine）上，基於Tornado的簡單的代碼分享網站。見：http://codeu.sinaapp.com

## 使用方法

> 1. 在 SAE 上新建 Python 應用，在`setting.py`中設置站點名，修改後上傳
> 2. 開啓MySQL服務，進入數據庫，導入db.sql
> 3. 編輯urls.py文件 取消對管理員帳號密碼設置的註釋 打開 http://youapp.sinaapp.com/admin/start 輸入你的管理員帳號（爲了安全，建議初始化後註釋urls.py文件中的對應網址）

## 一些特徵

用戶可以自由發佈代碼，擁有一個自己設定的密碼，用於修改和刪除自己的代碼，管理員可以刪除代碼，如果要修改只能去數據庫修改。

## License

See MIT-LICENSE.txt


本項目改造於 https://github.com/SerhoLiu/CodeShare 感謝!