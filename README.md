# li-projects
先向Git Code 里边的 li-projects 仓库里边添加要上传的代码
git add * 或者是 git add 需要上传的文件名
git commit -m "对上传的文件进行说明"
git status  //检查仓库情况
git push    //进行上传

在仓库进行修改之后使用 git pull 拉回到本地 就可以看到修改之后的文件

如果需要在网页查看 自己写的 则需要输入网址之后并且具体到要查看的东西 如  .....\mi.html

如果在本地文件中修改了某些文件内容或者是代码内容，修改之后可以进行查看（git status）

上面的命令告诉我们 readme.txt文件已被修改，但是未被提交的修改。
接下来我想看下readme.txt文件到底改了什么内容，如何查看呢？可以使用如下命令：
git diff readme.txt 

git diff顾名思义就是查看difference，显示的格式正是Unix通用的diff格式.