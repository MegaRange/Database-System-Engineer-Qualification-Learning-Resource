[初言难择选，何不学**[color=#2b5b84]Py[/color][color=#ffd343]thon[/color]**？](https://www.unitalk.fun/unitalk/public/d/22-python)
## [color=darkgreen]能不能把这课用人话讲好，让你们都能明白，就看我能不能行。[/color]
不对的地方要留言纠正我好改，Unitalk的初衷就是提供各种有用的信息。

### 1.下载Python
Windows不像Linux这样自带Python，所以，我们要去 https://www.python.org/downloads/ 下一个。
如果来试一试或者做一些简单的工作的话，可以去找互联网上的在线解释器。比如下面的这两个：
https://c.runoob.com/compile/6
https://www.makerbean.com/python_online （这特么还是网易的）
但是呢，如果要进行更深层次的学习，或者要用到外部库来创作你自己的作品，最好还是在电脑上装一个。

#### 那么，要选择哪个版本？

之前看过一门课，上面推荐“次新”的版本，目前（2020年5月3日）最新的版本是3.8.5。
那么我们就[点我下载3.7.8版本](https://www.python.org/ftp/python/3.7.8/python-3.7.8-amd64.exe)好了。
至于为什么么……因为每个Python每时每刻都在发展，新的版本都加一些新的功能和做一些调整，新功能我们可能暂时用不到，做的调整影响最大的是我们以后将要用到的“程序包（库）”，万一他们没及时跟进新版本呢？话是这么说，3.8出了挺久了⑧，不跟进新版本怕是要被淘汰啊。**不过这些都是后话了，并不影响我们刚开始的学习**。

就像[fa]nintendo[/fa]任天堂说的嘛，开发游戏要用成熟的不行的技术。熟就稳啊。

Python的安装嫌麻烦是可以直接“Install Now”的。
[size=20]但是注意啊！最下面那个“Add Python to PATH”一定要打勾☑。[/size]
安装到最后，推荐点一下那个去掉PATH最大字数限制的设置，没有的话，直接Close就好了。

### 2. 搞一个IDE（集成开发环境）
虽然Python可以用记事本写，但是使用一个IDE会更方便你写代码。
[center]IDE好处都有啥？谁说对了就给他！
代码高亮易理解，代码折叠省空间。
问题代码红色显，方便查找与Debug。
代码写完直接跑，运行结果早知道。
当然这些很基础，IDE功能无止境。
~注：只有Python和Javascript这类脚本语言的可以直接跑。~[/center]
比如我正在用的 VSCode。从这里下载： https://code.visualstudio.com/
不仅Python，很多与计算机程序相关的东西都可以用它来处理，它其实就是个专门为计算机科学开发的有更多功能的记事本。

安装也蛮简单。选好你要安装的位置，然后在“**选择其他任务**”那里，把“**添加到PATH**”勾上，剩下的看着勾。
安装完成后启动它，然而还要做一些工作。
比如可能你装好的VSCode的语言不是中文。这个时候你需要进行以下操作：

1. 使用`Ctrl+Shift+X`键，或者在左边点击四个方块的图标，打开“扩展程序”面板；
2. 在搜索框输入`Chinese`，第一个应该就是简体中文语言包，点击旁边小小的蓝色`Install`按钮安装之；
3. 使用`Ctrl+Shift+P`键，或者点击左下角的齿轮选择最上面的打开“命令面板”，这个“命令面板”在VSCode中经常用。记住这个按键组合吧！记成`CSP`。[color=gray]~（嗯？《反恐精英：移动版》？Counter ~Strike ~Portable）~[/color]
4. 输入`Configure Display Language`；
5. 点击下面出现的`zh_cn`，也就是中文；
6. 重启VSCode，它就会变成中文了。

中文更易于理解。不接受反驳，不接受抬杠。

还有你需要安装Python扩展，与刚才安装中文语言包差不多，在扩展里搜索“Python”安装它就可以了。

### 3. 事后……
至此，你的准备工作就完成了。
不仅是学习Python，Javascript和PHP等脚本语言都可以这么弄。

你现在可以尝试Python的各种打开方式了。
使用`Win+R`键打开启动，或者Windows 10直接按一下`Win`键，输入`python`或者`py`，启动Python。
注意Win10的这方法可能直接启动IDLE了，当然用IDLE更好啦，它是个学习工具，支持语法高亮。
你就可以在这里写Python代码了。

现在你打开了Python的交互式界面，你可以像输入命令一样输入Python代码，回车后结果。
你可以测试以下代码了，请尽量手打，不要复制粘贴：

1. 打印一串文字
```Python
print("啊啊啊啊啊啊啊")
```
2. 求平方
```Python
a = int(input("输入一个数字："))
## 注意：回车后你将被要求输入数字，输入一个数字并按回车后再开始下面的语句。
print(a**2)
```

在下一章，将为你介绍**[color=#2b5b84]Py[/color][color=#ffd343]thon[/color]**™[s]计算器的用法[/s]的数学运算。
[何不学Python：二、计算机就是为了计算](https://www.unitalk.fun/unitalk/public/d/53-python)