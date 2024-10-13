# git 配置步骤
```bash
# 第一步先点击github或者gitee目标仓库中右上角fork，fork到自己的仓库中
# 第二步在本地创建文件夹或者使用指令
mkdir Test
# 第三步在终端中输入以下命令
cd Test
sudo apt install git

git init
git config --global user.name "Your Name"
git config --global user.email "youremail@domain.com"

git remote add origin https://github.com/Your Name/2025_new_test.git
git pull origin Vice-branch
git add .
git commit -m "first commit"
git push -u origin master

# 第五步在github或者gitee中点击pull request
# 第六步创建request
```

# 培训进度
```mermaid
gantt
    title 团队任务进度
    dateFormat  YYYY-MM-DD
    section 成员A
    任务1 :done, task1, 2024-10-01, 2024-10-05
    任务2 :active, task2, 2024-10-06, 2024-10-15
    section 成员B
    任务1 :done, task3, 2024-10-03, 2024-10-07
    任务2 :active, task4, 2024-10-08, 2024-10-20
    section 成员C
    任务1 :done, task5, 2024-10-02, 2024-10-06
    任务2 :active, task6, 2024-10-07, 2024-10-12

```