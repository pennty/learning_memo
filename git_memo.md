# 让笔记和Github同步

### 建个github库
1. 在github上新建个库(注意不要选README,许可证声明什么,一定要生成个空的库)
2. 在本地上建个git库，也可以用已有的库
```bash
echo "# learning_memo" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/pennty/learning_memo.git
git push -u origin master
```

* 如果远程库写错了可以改
```bash
git remote -v   # 查看一下现在的远程库
git remote set-url origin {new url}     # 修改远程库
git remote rm destination    # 删除一个远程库
```

### 在线资源
* [30天精通 Git 版本控管](https://github.com/doggy8088/Learn-Git-in-30-days/blob/master/zh-tw/README.md "繁体的Git教程")


