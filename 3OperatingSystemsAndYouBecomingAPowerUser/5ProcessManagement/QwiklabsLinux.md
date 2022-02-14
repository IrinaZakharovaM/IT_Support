# Terminating a specific process

```
ps -aux | grep "totally_not_malicious"
sudo kill 1234
ps -aux | grep "totally_not_malicious"
```

# Terminating multiple processes

```
ps -aux | grep "razzle"
sudo kill 1235
sudo kill 1236
sudo kill 1237
ps -aux | grep "razzle"
```