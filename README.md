查询 Nginx 的进程 ID (PID):
     tasklist /FI "IMAGENAME eq nginx.exe"
使用 taskkill 命令强制停止 Nginx 进程：
     taskkill /PID 1234 /F