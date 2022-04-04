# LearnSpringBoot->wiki
## 常用调试命令
### 关闭8080端口占用进程
- 打开cmd确认进程  
 `netstat  -aon|findstr "8080"`  
- 关闭进程 如7724  
 `taskkill /F /PID 7244`
