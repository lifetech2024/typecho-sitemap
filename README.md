# typecho-sitemap
## 注意
请下载Releases的zip压缩包，把压缩包中Sitemap文件夹上传至/usr/plugins/
## 简介
基于其他项目修改bug，为作者自用（typecho插件）
## 使用说明
**提示：只适用于中国标准时区，其他时区在Action.php修改**

**更改时区**：

1.在代码第36行和第60行，把 `+08\:00` 更改。（如设置为东欧标准时间，把 `+08\:00` 改为 `+02\:00` ）

2.修改 `date_default_timezone_set('Asia/Shanghai');`   **注释：('')中填写php时区名称**

3.上传至/usr/plugins/目录，插件文件夹必须为Sitemap
