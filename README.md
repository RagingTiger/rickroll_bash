## About
Prank your macOS friends with a good 'ole fashion `Rick Roll` by executing the 
following command in a shell session on their machine:

```
$ curl -fsSL "https://raw.githubusercontent.com/RagingTiger/rickroll_bash/master/rickroll.txt" | while read line; do say "$line"; sleep 1; done
```

