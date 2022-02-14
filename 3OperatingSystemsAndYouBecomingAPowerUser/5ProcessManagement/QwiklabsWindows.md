# Terminating a specific process

```bash
Get-Process -Name "totally_not_malicious"
taskkill /F /PID 121
Get-Process -Name "totally_not_malicious"
```

# Terminating multiple processes

```bash
Get-Process -Name "*razzle*"
taskkill /F /PID 123
taskkill /F /PID 124
Get-Process -Name "*razzle*"
```