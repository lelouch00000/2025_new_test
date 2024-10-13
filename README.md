# git 配置步骤
```bash
sudo apt install git
在合适位置创建文件夹
mkdir Test
cd Test
git init
git config --global user.name "Your Name"
git config --global user.email "youremail@domain.com"

git remote add origin https://github.com/lelouch00000/2025_new_test.git
git pull origin master
git add .
git commit -m "first commit"
git push -u origin master

```

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