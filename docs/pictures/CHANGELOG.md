## 2021-04-19 `v0.1.0`
- 第一版

## 2021-04-20 `v0.1.1`
### 修复与改进
- 通过仅由renderer进程访问lowdb，绕过文件锁，修复cookie不同步的问题
- 获取活动时，增加提示

### 新增
- 基于intro.js，实现使用教程
- 日志增加“当前活跃课程”