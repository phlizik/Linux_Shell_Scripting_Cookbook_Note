### Chapter2 命令之乐
#### cat
`cat file1 file2 file3`：将 file1 file2 file3 内容拼接
`echo 'text through stdin' | cat - `：`-`被作为stdin的文件名
`cat -s file`：压缩相邻的空白行
`cat -T file`：显示制表符
`cat -n file`：输出行号

#### script & scriptreplay
`script -t 2>timing.log -a output.session` 开始录制
`scriptreplay timing.log output.session`

#### xargs
xargs命令把从stdin中的数据流重新格式化，再将其作为参数提供给其他命令。



