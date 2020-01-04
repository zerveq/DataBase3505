# DataBase3505
### UPD - 1.4
大更新 前端基本上写完了
界面简述
apply.html 教务处功能 - 处理教师开课的申请
arrange.html 教务处功能 - 查看排课的结果
opening.html 教师功能 - 教师开课
opening_result.html 教师功能 - 教师开课结果（教师开课提交表单后返回该界面）
state.html 教师功能 - 查看教师开课的状态
search.html 学生功能 - 查询对应时段对应地点的课程
search_result.html 学生功能 - 查询对应时段对应地点的课程的结果（学生查询提交表单后返回该界面）
### UPD - 12.30  
关于数据生成格式：  
学生 - 学号 姓名 学院 年级  
教师 - 教师编号 姓名 学院  
地点 - 地点编号 楼名 层数 教室编号 教室人数  
【特殊说明】  

| 楼名    | 层数 | 编号  | 人数                  |
| ------- | ---- | ----- | --------------------- |
| 公教1楼 | 6    | 01~05 | 50~100随机，整10倍数  |
| 公教2楼 | 3    | 01~22 | 30~50随机，整10倍数   |
| 公教3楼 | 5    | 01~12 | 100~200随机，整10倍数 |

时间 - 时间编号 起始时段 终止时段 对应时间

【特殊说明】  

| 起始时段 | 终止时段 | 对应时间    |
| -------- | -------- | ----------- |
| 1        | 2        | 8:00-9:30   |
| 3        | 4        | 10:00-11:30 |
| 5        | 6        | 12:00-13:30 |
| 7        | 8        | 14:00-15:30 |
| 9        | 10       | 16:00-17:30 |
| 11       | 12       | 18:00-19:30 |
| 13       | 14       | 19:30-21:00 |
| 1        | 3        | 8:00-10:30  |
| 4        | 6        | 2:00-4:30   |
| 11       | 14       | 6:00-9:00   |

开课表 - 开课编号 开课教师 课程名 班级编号 学分 课程人数 同伴老师1 同伴老师2

排课表 - 开课编号 时间编号 地点编号

**去除了课程表**

### UPD - 12.27  
注意 - 如果在linux下进行push，需要将CS_project中的settings.py重命名为settings_linux.py，方便对接
