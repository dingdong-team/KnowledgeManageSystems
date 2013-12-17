# Git的基本使用教程
### 注册帐户
建议使用自己常的邮箱，如QQ邮箱来作为注册邮箱，这样以后有什么任务或者是通知可以自动发邮箱通知给你。
### 在win7下安装git
在 http://git-scm.com/downloads 这个链接下载安装包，大约14M大小。启动安装，一路Next就可以了，安装路径什么的可以自己改。
### 在win7下使用git
#### 生成自己的SSH KEY
第一次使用的时候，建议如下使用：`开始菜单->Git->Git gui`，打开git gui后，选择`帮助->show SSH Key`，选择`Generate Key`，然后根据提示输入你的帐户名和邮箱，密码等信息，还要输入一个口令，你可以随便输入，这个口令相当密码的作用。输入完后会生成你的SSH KEY，然后点击`Copy to Clipboard`。
#### 设置自己的SSH KEY
在 http://github.com 登录，在`页面右上角`点击`Account Setting`，就是类似扳手一样的图标。然后在左侧点击`SSH KEYS`，再点击`Add SSH Key`。`title`自己输入，`SSH KEY`直接把上一步复制的`SSH KEY`填入。
#### 获取项目
打开`开始菜单->Git->Git bash`，转到自己想要存储项目的地方，比如我要转到`d:\DevelopmentProject\JavaPorject`，那么我就输入：

```
cd d: //转到d盘
cd DevelopementProject //转到子目录
cd JavaProject //转到子目录
```
>注意：文件名和目录名不可以有空格！
转到当前目录之后，我们把项目复制下来

```
git clone https://github.com/dingdong-team/KnowledgeManageSystems.git
```
这样所有文件就会复制到本地文件夹里，在`d:\DevelopmentProject\JavaPorject`下会有一个名字为`KnowledgeManageSystems`的文件夹，里面有这个项目的所有文件。
