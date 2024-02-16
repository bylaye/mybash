# mybash
Some command BASH 

## Get size file and directory

* Get the size human readable (G, M, K) of all files and directories
```
du -sh *
```

* Sorted by size
```
du -sh * | sort -h
```

* Sorted by size desc
```
du -sh * | sort -hr
```


* Sorted by size desc list top ten
```
du -sh * | sort -hr | head -n 10
```


