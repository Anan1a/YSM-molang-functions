# 函数包（pack）（为了运行效率将依赖写进一个函数，仅存在依赖的开放函数会被打包）
以`pack`做前缀  
例：`pack`  

特殊规则，`pack`+`函数名`，为该函数的打包版

|后缀|函数|返回值|
|---|---|---|
|stat_pos_diff|pack_stat_pos_diff(pos_diff)|pos_diff|
|stat_pos_dsum|pack_stat_pos_dsum(pos_dsum)|pos_dsum|

[返回](./_README.md)
