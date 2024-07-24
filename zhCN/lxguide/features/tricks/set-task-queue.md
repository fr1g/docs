# 任务中心队列机制 -- 为什么我不能同时跑三个以上的游戏？

LauncherX使用一套独特的并行任务管理机制，使得启动器在有完整的对游戏状态监控的同时，处理其他事务。

鉴于使用LauncherX的设备性能可能参差不齐，而同时运行大量任务可能带来卡顿，所以我们**暂未**在设置中留下任务并行数量的明确设置。这个设置的默认值为3。

如果您觉得自己的设备具备强大的并行能力，只需要遵循以下步骤，来按需调整并行量：

1. 关闭LauncherX（可选），前往LauncherX目录  （这个目录是和默认游戏目录和LauncherX.json同级的）
2. 在其中新建文件，命名为`SET_TASK_QUEUE_SIZE`，不要给它留下后缀名
3. 用喜欢的文本编辑器打开它，并且输入一个你需要的并行数量的阿拉伯数字，不得填入除了数字以外的任何其他字符
4. 重新打开LauncherX，即可应用新指定的并行任务数量设置。