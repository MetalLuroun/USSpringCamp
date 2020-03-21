# USSpringCamp
## 进展
基本完成了所有的功能,
* 用户注册/登录
* 情绪打捞
* 情绪记录
* 情绪上传
* 用户信息统计




但还缺少一些存在重复性的工作以及一些未能解决的问题


比如:
* 情绪搜索中的 负情绪搜索未完成(基本与积极情绪相同
* 视觉可视化使用了假数据,后端没有提供相应接口
* 搜索功能的后台接口似乎只能接受数字而不是字符串,需要再跟后端协商一下
* 图片上传API要求上传二进制文件,但经过formdata的传输会导致文件被添加请求头,最后破坏了png的原有格式导致取得的图片无法解析(这一部分不是我做的所以我也不是很清楚具体情况....

其余功能基本都可以使用
