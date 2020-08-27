### エラーが出力する場合

以下のようなエラーが出力した場合は、スクリプトを後述の通り実行ください。
![image](/images/pserror.png)

```powershell
Powershell.exe -ExecutionPolicy ByPass -Command {.\Get-AADCDiagData.ps1 -Logpath <ログファイル出力先> }
```
