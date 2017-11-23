## About
Prank your macOS friends with a good 'ole Rick Roll. To execute, just get 
access to a shell session on their machine and choose one of the following:

### Execute Directly
```
$ curl -fsSL "https://raw.githubusercontent.com/RagingTiger/rickroll_bash/master/rickroll.txt" | while read line; do echo "$line" && say "$line"; sleep 1; done
```

### Append to RC file
```
$ echo 'curl -fsSL "https://raw.githubusercontent.com/RagingTiger/rickroll_bash/master/rickroll.txt" | while read line; do echo "$line" && say "$line"; sleep 1; done' >> ~/.$(basename $SHELL)rc
```

