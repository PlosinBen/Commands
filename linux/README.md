
新增使用者
```cmd
adduser <*username> <groupname>
```

新增群組
```cmd
addgroup <groupname>
```

授予sudo權限
```cmd
usermod -aG sudo <username>
```

ssh key加入清單
```cmd
cat <sshpubfile> >> ~/.ssh/authorized_keys
```

顯示message queue狀態
```cmd
ipcs -q
```
