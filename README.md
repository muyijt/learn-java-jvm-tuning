# learn-java-jvm-tuning
学习java的jvm调优

## jps
- 查找所有应用的进程号

## jmap

### 查看某个进程的内存，实例个数等信息
- jmap -histo 进程号 > ./log.txt

### 导出某个进程的堆内存快照
- jmap -dump:format=b,file=aa.dump 进程号