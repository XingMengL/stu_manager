# 第一步.开始学生信息管理项目：
#     需要两个函数：
#     input_student() 返回学生信息的字典的列表
#     output_student(lst) 以表格方式打印学生信息
#     学生信息：
#         姓名(name)    字符串
#         年龄(age)     整数
#         成绩(score)   整数

# 第二步.改写之前的学生信息管理项目源码，要求带有操作界面:
#     +-----------------------------+
#     |1)添加学生信息                 |
#     |2)显示所有学生的信息            |
#     |3)删除学生信息                 |
#     |4)修改学生成绩                 |
#     |5)按学生成绩高-低显示学生信息    |
#     |6)按学生成绩低-高显示学生信息    |
#     |7)按学生年龄高-低显示学生信息    |
#     |8)按学生年龄低-高显示学生信息    |
#     |q)退出                       |
#     +----------------------------+
#     要求每个功能至少写一个函数与之相对应

# 第三步：
# 1.修改原来的学生信息管理系统的代码，将其分为模块，
# 建议：
#     1）把显示菜单放在一个模块内
#     2）把学生的操作放在一个模块内
#     3）把主事件循环while True选择输入放在一个模块内
# 2.在菜单上添加两个功能：
#     1）保存学生信息到文件(si.txt)
#     2）从文件中读取数据(si.txt)
# 建议用','分隔数据：
#     #file: si.txt
#     xiaozhang,21,98
#     xiaoli,22,100
#     ...

#第四步：
#1）看懂学生管理系统(老师的代码)划分模块的依据
#2）添加保存文件和读取文件的代码
#3）把字典改为对象来存储数据
#(最好把学生对象的实例变量都封装在类内，让类外的函数最好不要操作这些实例变量)

#第五步：
1.扩展学生信息管理系统，试想能否在不改变原Student类的基础上为每个学生添加一个家庭住址的信息？
2.添加修改家庭住址的功能