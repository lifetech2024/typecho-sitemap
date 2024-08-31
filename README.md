# typecho-sitemap
## 简介
基于其他项目修改bug，为作者自用
## 使用说明
**提示：只适用于中国标准时区，其他时区在Action.php修改**

**更改时区**：
1.在代码第36行和第60行的'Y-m-d\TH:i:s\+08\:00'，把+08\:00更改。（如设置为东欧标准时间，把+08\:00改为+02\:00）

2.插入date_default_timezone_set('Asia/Shanghai'); 
