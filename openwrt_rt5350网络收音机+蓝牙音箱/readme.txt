

//注意 上电默认暂停  发播放指令播放 AA 01 17 02 EE  系统默认 播完完一曲后  接着播放下一曲  播放完最后一曲后 循环播放第一曲


播完完毕返回指令 AA AA AA AA 

播放完一曲完毕后暂停指令  AA 00 05 EE 

解除播完完一曲完毕后暂停命令 AA 00 25 EE  

//  RX P25  TX P24    波特率 19200


//注意 上电默认暂停 系统默认 播完完一曲后  接着播放下一曲  播放完最后一曲后 循环播放第一曲


播完完毕返回指令 AA AA AA AA 

播放完一曲完毕后暂停指令  AA 00 05 EE 

解除播完完一曲完毕后暂停命令 AA 00 25 EE      
 


指定播放曲目： AA 02 11 00 03 EE 
AA 00 12 EE  播放上一曲
AA 00 13 EE  播放下一曲
AA 00 14 EE  音量减少一级
AA 00 15 EE  音量增加一级
AA 01 16 10 EE  音量的值为0-30
AA 01 17 01 EE  暂停
AA 01 17 02 EE  播放
AA 01 18 02 EE 设置EQ模式为ROCK
AA 01 19 01 EE 设置单曲循环模式
AA 04 1a 00 02 01 20 EE  指定U盘的第2首歌曲从1分32秒处开始播放。
AA 04 1c 00 03 01 20 EE  指定当前盘符的第3首歌曲从1分32秒处开始播放。
AA 02 1d 01 20 EE  指定到1分32秒处开始播放。
/广告  /联想*MP3
AA121E2FB9E3B8E6202020202FC1AACFEB2A4D5033EE  指定路径
AA 00 22 EE  提前结束插播的歌曲或广告。
AA 路径数据长度 24 路径 EE 
例如：插播小米广告
/广告  /小米手机MP3
AA15242FB9E3B8E6202020202FD0A1C3D7CAD6BBFA4D5033EE 用这个可以 
/广告  /小米*MP3
AA12242F B9E3 B8E6 20 20 20 20 2F D0A1 C3D7 2A 4D 50 33 EE 这样也可以
/广告  /小米????MP3
AA15242F B9E3 B8E6 20 20 20 20 2F D0A1 C3D7 3F 3F 3F 3F 4D 50 33EE  这样也可以






/广告  /小米手机MP3

AA151E2FB9E3B8E6202020202FD0A1C3D7CAD6BBFA4D5033EE 用这个可以
 

/广告  /小米*MP3

AA121E2F B9E3 B8E6 20 20 20 20 2F D0A1 C3D7 2A 4D 50 33 EE 这样也可以

/广告  /小米????MP3

AA151E2F B9E3 B8E6 20 20 20 20 2F D0A1 C3D7 3F 3F 3F 3F 4D 50 33EE  这样也可以

 经验  要注意如果是复制过去空格会不同，要注意空格数，最好是在 路径取模工具.exe里写
/广告  /品牌运动服装清仓处理广告录音通用MP3

/广告  /品牌*MP3

AA121E2F B9E3 B8E6 20 20 20 20 2F C6B7 C5C6 2A 4D 50 33 EE

/广告  /联想*MP3

AA121E2F B9E3 B8E6 20 20 20 20 2F C1AA CFEB 2A 4D 50 33EE  指定路径

AA12242F B9E3 B8E6 20 20 20 20 2F C1AA CFEB 2A 4D 50 33EE   指定插播广告

AA12242F B9E3 B8E6 20 20 20 20 2F C6B7 C5C6 2A 4D 50 33 EE

