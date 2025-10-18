# 获取（get）
以`get`做前缀  
例：`mc_get`

|前缀|操作|函数|返回值|
|---|---|---|---|
|absPos|获取绝对坐标|mc_get_absPos(name)|vector_3|
|prevRot|获取上一帧旋转|mc_get_prevRot(name)|vector_3|
|prevScale|获取上一帧缩放|mc_get_prevScale(name)|vector_3|
|relPos|获取相对坐标|mc_get_relPos(name)|vector_3|
|worldpos|获取在世界上的坐标|mc_get_worldpos|vector_3|
|worldposd|获取自上次运动的坐标差值|mc_get_worldposd|vector_3|

[详情](./mc__README.md)
