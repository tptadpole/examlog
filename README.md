## 想法

composer.json需要一個套件
這個套件在"https://github.com/tptadpole/logger"
所以我需要先在自己的github上建立一個logger的repo

然後在我自己的電腦上初始化composer.json檔 所以在終端機下composer init
接著自己根據run.php去寫logger內需要什麼
把我寫好的logger加到composer的autoload裏
push到github上的repo裡

這樣別人就可以git clone我的檔案
autoload我寫好的logger
順利執行run.php並得到理想的結果

目前應該是完成了 我在本機上測試沒問題
如果有問題再告訴我
