**管理権限ない時の　PATH 設定**

[参考１](https://qiita.com/asterisk9101/items/7f1924a1402a4c9825e7)
[参考２](http://www.ne.jp/asahi/hishidama/home/tech/windows/cmd/cmd.html#AutoRun)


```
init.bat
set PATH=C:\temp\bat\;%PATH% 
```

HKEY_LOCAL_MACHINE\Software\Microsoft\Command Processor	マシン
HKEY_CURRENT_USER\Software\Microsoft\Command Processor	現在のユーザー

regedit（レジストリエディタ）でなら、「HKEY_*」→「Software」→「Microsoft」→「Command Processor」を右クリックし、「新規(N)」→「文字列値(S)」で、「名前」に「AutoRun」を入力する。
その後、「AutoRun」の文字を右クリックして「修正(M)」で「文字列の編集」ダイアログを出し、「値のデータ(V)」にデータ（上記の例なら「c:\bin\cmd_init.bat」）を入力する。
