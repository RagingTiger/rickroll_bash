## About
Prank your macOS friends with a good 'ole Rick Roll. Two options for the 
prank:

### Execute Directly
```
$ curl -fsSL "https://raw.githubusercontent.com/RagingTiger/rickroll_bash/master/rickroll.txt" | while read line; do say "$line"; sleep 1; done
```

### Append to RC file
```
$ echo 'curl -fsSL "https://raw.githubusercontent.com/RagingTiger/rickroll_bash/master/rickroll.txt" | while read line; do say "$line"; sleep 1; done' >> ~/.$(basename $SHELL)rc
```

