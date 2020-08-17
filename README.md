# What affects learning(Data Analysis)
 数据分析 EDA-什么因素如何影响到学习


# Data
## Data Source
- 这些数据是一个葡萄牙上学的同学的作业提供的。 
它包含许多有关学生的有趣的社交，性别，学习信息和家庭信息。 
可以将其用于一些EDA之类的。

## Data Type
- School：就读学校，GP-Gabriel Pereira ,MS - Mousinho da Silveira
- Sex: 性别，F-女生，M-男生
- age: 年龄，从15-22
- address:家庭地址，分为U-城市与R-农村
- famsize: 家庭人口,LE3-不超过3人，GT3-超过3人
- Pstatus: 父母的状态，A-分居还是T-一起生活
- Medu: 母亲的受教育程度，0-没有受过教育，1-低等教育，4-高等教育
- Fedu: 父亲的受教育程度，0-没有受过教育，1-低等教育，4-高等教育
- Mjob：母亲的工作，老师, 健康管理员, 城市服务者（警察或政府人员）、待在家里 or 'other'
- Fjob：父亲的工作，老师, 健康管理员, 城市服务者（警察或政府人员）、待在家里 or 'other'
- reason: 选择这个学校的原因，home-离家近，reputation-学校名誉，course-课程原因
- guardian: 学生监护人，mother-母亲，father-父亲，other-其他人
- traveltime: 上学的用时，1(<15 min.), 2(15 to 30 min.), 3(30 min. to 1 hour), 4(1 hour)
- studytime: 一周学习的时长, 1(<2 hours),2(2 to 5 hours), 3(5 to 10 hours), 4 (<10 hours)
- failures: 班级上一些不愉快的事情发生的次数,0-最少，3-最多
- schoolsup: 额外的高费用教育支出，比如开培训班，yes-是，no-否
- famsup: 额外的家庭教育支出，比如父母经常陪家里的孩子，yes-是，no-否
- paid：是否给孩子开设收费的自费课程，yes-是，no-否
- activities：学生的课外活动是否足够多，yes-是，no-否
- nursery：学校是不是有专门的学生保健医师，yes-是，no-否
- higher：学生是否想要去接受更高的教育，yes-是，no-否
- internet： 在家一周是否上网，yes-是，no-否
- romantic： 是否谈恋爱，yes-是，no-否
- famrel：家庭质量，1-非常差，5-非常好
- freetime：在放学后的课余时间，1-非常短，5-非常长
- goout：经常与朋友出去玩，1-非常少，5非常多
- Dalc：工作日饮酒次数，1 - 非常少 to 5 - 非常多
- Walc： 周末饮酒次数，1 - 非常少 to 5 - 非常多
- health： 健康状况，1 - 非常坏 to 5 - 非常好
- absences：缺勤率，0-0%，93-93%
- G1: 分数1，0 to 20
- G2：分数2, 0 to 20
- G3：分数3（本文主要用的是这个分数）,0 to 20

# Technology
## Installation
``` pip install numpy matplotlib plotly pandas
# Conclusion
- 有优秀成绩的秘诀吗？ of course, 
- 给足够的时间学习
- 不要只顾着谈恋爱，谈恋爱的同学在学习时长上花费的少一些
- 家庭关系要相处的好，父母在家一起陪孩子学习会更好
- 不要滥用酒精，酒精使用过度会降低学习的欲望，减少学习的时间，成绩也会受影响
- 上网时间要学会控制
- 学习好之外，身体也要healthy
- 学习不好的话，缺勤率也会高，所以减少缺勤哦
- 城市的学生学习时长更长，学习成绩相对于乡村中的学生要好一些，在路上花费的时间会更短
- 有一个很好地接受高等教育的心愿的同学学习动力更大
