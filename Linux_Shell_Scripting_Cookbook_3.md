### Chapter3 文件之名

#### dd
创建特定大小的文件的最简单方法就是使用`dd`命令。
```
$ dd if=/dev/zero of=junk.data bs=1M count=1
```
该命令会创建一个1MB大小的文件junk.data。`if`代表输入文件（input file）, `of`代表输出文件，`bs`代表以字节为单位的块大小，`count` 代表需要被复制的块数。
/dev/zero 是一个字符设备，它会不断返回`0`值字节(`\0`)

#### common

