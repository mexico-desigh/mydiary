# 酷gril计划

##### 一、前端页面结构

1. 酷gril

       -  主题
           - 改变背景
       -  
       -  
       -  

2. 计划

       - 小目标
           - 点进去填写年计划、月计划、周计划、日计划   ***** 新页面 Year Month Week Day
       - 随手记
           - 点进去记录当前的想法         ***** 新页面  Idea
       - 心情
           - 点击弹出弹框选择今天的心情     ——————弹框组件 Mood
       - 笔记
           - 点进去记录今天学到的东西     ***** 新页面 Note

3. 计划列表

       - 展示心情 并写一句鼓励的话
       - 年计划、月计划、周计划、日计划    展示在当前页面 ^_^
           - 一年里面的每个月的计划
              - 一个月里面的每个星期的计划
                  - 一个星期里面的每一天的计划

4. 酷gril计划数据统计

       - 日历
           - 有记录的那天标记深色
           - 点进去显示当天的记录内容     ***** 新页面 Record

##### 二、数据库设计

1. 个人信息表
       - name   -char (P)
       - id   int (F)
2. 年计划表
       - id   int (P)
       - years date
       - content text
3. 月计划表
       - id   int (P)
       - months date(F)
       - content text
4. 周计划表
       - id   int (P)
       - weeks date(F)
       - content text
5. 日计划表
       - id   int (P)
       - days date(F)
       - content text
6. 心情表
       - id   int (P)
       - day  date(F)
       - mood char ------ 限选
7. 笔记表
       - id   int (P)
       - title char
       - content text
8. 随手记表
       - id   int (P)
       - title char
       - content text
