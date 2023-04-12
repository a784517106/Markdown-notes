# *TECHNOLOGY*

## *New Bing可以进入对话界面但无法进行对话*

​		访问New Bing显示**Sorry, looks like your network settings are preventing access to this feature.**怎么解决

这个问题可能是由于你的浏览器插件或网络设置导致的。根据搜索结果¹²³⁴，你可以尝试以下几种方法：

- 关闭或卸载任何可能影响重定向的插件，如Header Editor，ModHeader等。
- 重置浏览器设置，清除浏览器历史记录。
- 升级Edge浏览器到最新版本。
- 升级Windows 10到最新版本。
- **更换账号或节点（亲测有效）**

希望这些方法能帮助你解决问题。😊

源: 与必应的对话， 2023/3/24(1) CSDN - New Bing 提示Sorry, looks like your network settings are .... https://bing.com/search?q=%e8%ae%bf%e9%97%aeNew+Bing%e6%98%be%e7%a4%baSorry%2c+looks+like+your+network+settings+are+preventing+access+to+this+feature.%e6%80%8e%e4%b9%88%e8%a7%a3%e5%86%b3 访问时间 2023/3/24.
(2) 使用new bing报错的解决办法 - 知乎. https://zhuanlan.zhihu.com/p/615145280 访问时间 2023/3/24.
(3) 解决New必应无法访问:Sorry, looks like your network settings are preventi. https://www.bilibili.com/read/cv22435955/ 访问时间 2023/3/24.
(4) 完美解决NewBing-Sorry, looks like your network settings are preventing .... https://zhuanlan.zhihu.com/p/616339107 访问时间 2023/3/24.



## *Bat语言*

​		**bat文件用的是什么语言，这个语言跟c语言有什么关系**

根据搜索结果¹²³⁴⁵，bat文件用的是一种简化的脚本语言，也称为批处理语言或者宏语言，它应用于DOS和Windows系统中，是由系统内嵌的命令解释器（通常是COMMAND.COM或者CMD.EXE）解释运行。bat文件的扩展名为.bat或者.cmd，它可以用来批量执行一些DOS命令或者其他程序，实现自动化的操作。

这个语言跟C语言有一些相似之处，比如都可以使用if，for，goto等命令控制程序的运行逻辑，都可以使用变量，字符串，数值等数据类型，都可以使用echo命令输出信息。但是也有很多不同之处，比如bat文件的语法更简单，没有复杂的数据结构和函数定义，没有指针和内存管理，没有严格的类型检查和错误处理，没有面向对象和多线程的特性等。总的来说，bat文件是一种比较低级和有限的脚本语言，它主要用于简单的批量操作和系统管理，而不适合开发复杂的应用程序。

源: 与必应的对话， 2023/3/24(1) bat脚本：快速入门_csfchh的博客-CSDN博客. https://blog.csdn.net/csfchh/article/details/106795352 访问时间 2023/3/24.
(2) 解放双手！ bat 批处理自动化运行程序 - 知乎. https://zhuanlan.zhihu.com/p/125033413 访问时间 2023/3/24.
(3) 批处理_百度百科. https://baike.baidu.com/item/%E6%89%B9%E5%A4%84%E7%90%86/1448600 访问时间 2023/3/24.
(4) bat脚本：快速入门_csfchh的博客-CSDN博客. https://blog.csdn.net/csfchh/article/details/106795352 访问时间 2023/3/24.
(5) bat（批处理文件类型）_百度百科. https://baike.baidu.com/item/BAT/365230 访问时间 2023/3/24.

### *Bat语言的注释问题*

​		**bat语言做注释只能单独另起一行吗，能否在bat语言的一句代码的那一行后面直接做注释呢？**

根据搜索结果¹²³，**bat语言做注释只能单独另起一行，不能在bat语言的一句代码的那一行后面直接做注释**。bat语言的注释有以下几种方法：

1. 使用::符号，如::这是注释。这个符号是利用了定义标签的功能来实现注释，不会被执行或者回显。注意第一个冒号后也可以跟任何一个非字母数字的字符，如:?这是注释。
2. 使用rem指令，如rem这是注释。这个指令是用来添加注释的，但是会被回显在屏幕上，除非使用@或者echo off将其隐藏。注意不能出现重定向符号和管道符号。
3. 使用echo指令，如echo这是注释>nul。这个指令是用来输出文本的，但是可以通过重定向到nul来实现注释的效果。注意不能出现重定向符号和管道符号。
4. 使用goto指令，如goto label ... :label。这个指令是用来跳转到某个标签处执行的，可以利用它将一段不会被执行的代码作为注释。
5. 使用if指令，如if 1==0 (...)。这个指令是用来进行条件判断的，可以利用它将一个永远不成立的条件作为注释。

以上是bat语言的注释方法，希望能对你有所帮助。

源: 与必应的对话， 2023/3/24(1) 一篇文章彻底搞清楚Windows系统批处理脚本.bat文件的注释_bat脚本注释_全栈老司机的博客-CSDN博客. https://blog.csdn.net/qq_35421305/article/details/115208862 访问时间 2023/3/24.
(2) bat脚本积累（三）—— bat的注释_bat 注释_ProLayman的博客-CSDN博客. https://blog.csdn.net/ProLayman/article/details/104553433 访问时间 2023/3/24.
(3) bat中代码注释的几种方法-百度经验. https://jingyan.baidu.com/article/6fb756ec52ddd1241858fb05.html 访问时间 2023/3/24.



​		**使用rem指令，如rem这是注释。这个指令是用来添加注释的，但是会被回显在屏幕上，除非使用@或者echo off将其隐藏。注意不能出现重定向符号和管道符号。 能否为这个指令写几个范例？**

rem指令是用来在批处理文件中添加注释的，它不会影响程序的执行，只是为了方便阅读和理解。你可以使用以下格式来写rem指令：

rem 这里写注释内容

或者

@rem 这里写注释内容

或者

echo off
rem 这里写注释内容
echo on

例如：

rem 这个批处理文件是用来备份我的文档的
@rem 使用xcopy命令复制文件夹
echo off
rem 检查目标文件夹是否存在，如果不存在则创建
echo on

​		**使用echo指令，如echo这是注释>nul。这个指令是用来输出文本的，但是可以通过重定向到nul来实现注释的效果。注意不能出现重定向符号和管道符号。 能否再具体解释一下这句话的意思，最好举点例子**

echo指令是用来在屏幕上显示文本的，你可以使用以下格式来写echo指令：

echo 这里写文本内容

或者

@echo 这里写文本内容

例如：

echo 这是一个测试
@echo 这也是一个测试

如果你不想让文本显示在屏幕上，你可以使用重定向符号>来把文本输出到其他地方，比如文件或者设备。nul是一个特殊的设备，它会忽略任何输入，相当于一个黑洞。所以，如果你把文本重定向到nul，就相当于把文本丢弃了，这样就可以实现注释的效果。你可以使用以下格式来写echo指令：

echo 这里写注释内容>nul

或者

@echo 这里写注释内容>nul

例如：

echo 这个批处理文件是用来备份我的文档的>nul
@echo 使用xcopy命令复制文件夹>nul



### ***Path路径的添加问题***

​		***bat文件里path的用法***

![image-20230327151319379](Knowledge%20I%20learned%20by%20chance.assets/image-20230327151319379.png)

抱歉，我之前误解了你的问题。bat文件里path的用法是用来设置或修改环境变量path的值，path是一个环境变量，它指定了系统在执行程序时搜索的路径¹。如果你想在bat文件中运行一些程序，而这些程序不在当前目录或者系统目录下，你就需要在path中添加这些程序所在的路径，否则系统会找不到这些程序¹。

有两种方法可以在bat文件中设置或修改path的值，一种是使用set命令，另一种是使用setx命令¹。两种方法的区别是：

- set命令只能临时修改环境变量，只对当前控制台有效，关闭控制台后失效¹。例如：

**set PATH=%PATH%;D://ModelSim//bin**

这样就在path的原有值后面添加了D://ModelSim//bin这个路径¹。

- setx命令可以永久修改环境变量，对所有控制台和程序有效，但需要重启控制台或者电脑才能生效¹。例如：

**setx PATH "%PATH%;D://ModelSim//bin"**

这样就在path的原有值后面添加了D://ModelSim//bin这个路径，并保存到注册表中¹。

注意，在使用setx命令时，需要用双引号包围path的值，以避免空格或其他特殊字符造成错误¹。另外，如果要修改系统环境变量而不是用户环境变量，需要添加/m选项，并以管理员身份运行bat文件¹。例如：

setx PATH "%PATH%;D://ModelSim//bin" /m

这样就在系统环境变量path的原有值后面添加了D://ModelSim//bin这个路径，并保存到注册表中¹。

源: 与必应的对话， 2023/3/27(1) 批处理文件bat设置环境变量path - 酷熊 - 博客园. https://www.cnblogs.com/coolbear/p/13206215.html 访问时间 2023/3/27.
(2) bat脚本中 %cd%及 %path%的含义_modi000的博客-CSDN博客. https://blog.csdn.net/modi000/article/details/108319717 访问时间 2023/3/27.
(3) 批处理(.bat)文件中找不到文件等路径问题_运行bat找不到路径_feiyu68的博客-CSDN博客. https://blog.csdn.net/feiyu68/article/details/120092107 访问时间 2023/3/27.
(4) 批处理（bat）中路径名称或者文件名称有空格怎么办？_bat路径有空格怎么执行_大雄Obear的博客-CSDN博客. https://blog.csdn.net/bigbear00007/article/details/105759370 访问时间 2023/3/27.

***		path=C:/modeltech64_10.4/win64 那我这样写能够起到修改path的作用吗***

![image-20230327151013456](Knowledge%20I%20learned%20by%20chance.assets/image-20230327151013456.png)

这样写不能起到修改path的作用，因为你没有使用set或setx命令，只是定义了一个变量path，而不是修改环境变量path。如果你想临时修改path的值，你可以写：

set PATH=C://modeltech64_10.4//win64

这样就把path的值设置为C://modeltech64_10.4//win64，但是只对当前控制台有效，关闭控制台后失效。如果你想永久修改path的值，你可以写：

setx PATH "C://modeltech64_10.4//win64"

这样就把path的值设置为C://modeltech64_10.4//win64，并保存到注册表中，对所有控制台和程序有效，但需要重启控制台或者电脑才能生效。



## *PowerShell*

### ***PowerShell和cmd的区别***

​		***PowerShell为什么不支持cmd命令？他们之间有什么关系？***

PowerShell和cmd的关系是，它们都是Windows操作系统下的命令行工具，但是它们有很多不同的地方¹。PowerShell是基于.NET框架的，可以调用.NET的很多功能，而cmd是基于DOS的，只能执行基本的任务²。PowerShell是面向对象的，可以处理.NET对象，而cmd是面向过程的，只能处理文本³。PowerShell有自己的语法和参数，和cmd不完全兼容⁴。PowerShell可以执行cmd的命令，但是cmd不能执行PowerShell的命令⁵。

所以，你在PowerShell中使用了一个cmd的命令，但是PowerShell不支持这个命令的参数，就会报错。你可以使用PowerShell自己的命令来代替，或者在PowerShell中切换到cmd模式来执行。

源: 与必应的对话， 2023/3/27(1) PowerShell 与 cmd 有什么不同？ - 知乎. https://www.zhihu.com/question/22611859 访问时间 2023/3/27.

(2) cmd和PowerShell的区别_cmd powershell_孤独的代码的博客-CSDN博客. https://blog.csdn.net/weixin_48885539/article/details/106924767 访问时间 2023/3/27.
(3) CMD和Powershell区别 - 知乎. https://zhuanlan.zhihu.com/p/390464588 访问时间 2023/3/27.
(4) powershell和cmd区别是什么-常见问题-PHP中文网. https://www.php.cn/faq/467380.html 访问时间 2023/3/27.
(5) cmd、powerShell、终端或Terminal的区别？简单理解他们之间的关系！ - lYaao - 博客园. https://www.cnblogs.com/lyaao/p/14485311.html 访问时间 2023/3/27.



## *Modelsim*

### *修改了系统变量和环境变量依旧在脚本中无法调用vlib、vlog和vsim指令*

![image-20230327110111532](Knowledge%20I%20learned%20by%20chance.assets/image-20230327110111532.png)

但<font color='red'>**单独输入vlib指令是不报错的**</font>，所以我觉得**<font color='red'>系统变量的添加是有效的</font>**

![image-20230327110558648](Knowledge%20I%20learned%20by%20chance.assets/image-20230327110558648.png)

所以我决定**删除变量再重启命令行并输入vlib指令**试试

![image-20230327103348419](Knowledge%20I%20learned%20by%20chance.assets/image-20230327103348419.png)

删除路径后发现果然无法识别指令，说明变量添加确实是有效的

但是为什么在非原路径下还是会提示不是内部指令呢？

我猜测是<font color='red'>**代码中path的设定出现了问题**</font>

![image-20230327111008240](Knowledge%20I%20learned%20by%20chance.assets/image-20230327111008240.png)

修改为
![image-20230327111037417](Knowledge%20I%20learned%20by%20chance.assets/image-20230327111037417.png)

依旧报无法识别的错误

于是我尝试**去原路径运行脚本**

![image-20230327111203885](Knowledge%20I%20learned%20by%20chance.assets/image-20230327111203885.png)

成功运行了一部分：

忽略前面的一大堆error，最后还是出现了<font color='orange'>**无法识别secureip指令的问题**</font>

![image-20230327111522374](Knowledge%20I%20learned%20by%20chance.assets/image-20230327111522374.png)

有没有一种可能是<font color='red'>**脚本只能在Modelsim所在的路径下运行**</font>？

但是**单独执行vlib指令**可以通过，说明这个猜想大概率是错的

![image-20230327152713249](Knowledge%20I%20learned%20by%20chance.assets/image-20230327152713249.png)

**单独执行rd指令**，发现语法不支持，这是因为<font color='red'>**rd指令是Windows的cmd指令，需要输入cmd进入cmd模式后才能通过**</font>![image-20230327160124336](Knowledge%20I%20learned%20by%20chance.assets/image-20230327160124336.png)

cmd后输入rd work /s/q通过（文件已删所以显示找不到指定文件），然后exit退出cmd模式

![image-20230327160457144](Knowledge%20I%20learned%20by%20chance.assets/image-20230327160457144.png)

但是问题又来了，在<font color='orange'>**bat文件输入cmd来进入cmd模式好像是不能通过的**</font>，那么我们如何在脚本中使用rd指令呢？？？

另外，**PowerShell自身有删除文件夹和目录的语法**：

**Remove-Item <path> -Recurse -Force**

其中是要删除的目录的路径，-Recurse表示递归删除子目录和文件，-Force表示强制删除，不提示确认

![image-20230327161245935](Knowledge%20I%20learned%20by%20chance.assets/image-20230327161245935.png)

这个语法在PowerShell里也是可以通过的，**但也不能直接写到bat文件里**？？？

（另外也尝试过**在cmd中运行bat**，结果还是指令无法识别）

![image-20230327163218724](Knowledge%20I%20learned%20by%20chance.assets/image-20230327163218724.png)

Bing说有可能是**PowerShell执行策略错误**：

根据网上的一些资料¹²³，这个问题可能是由于PowerShell的执行策略导致的。PowerShell的执行策略是用来控制脚本文件是否可以运行的。默认情况下，PowerShell的执行策略是Restricted，也就是不允许任何脚本运行。

你可以使用`Get-ExecutionPolicy`命令来查看当前的执行策略，如果是Restricted，你可以尝试使用`Set-ExecutionPolicy`命令来修改执行策略为RemoteSigned或者Unrestricted，这样就可以允许本地或者所有的脚本运行了。

注意：修改执行策略可能需要管理员权限，而且可能会带来一些安全风险，请谨慎操作。

源: 与必应的对话， 2023/3/27(1) powershell提示无法将“”项识别 - 大耳朵小虎 - 博客园. https://www.cnblogs.com/wangrui38/p/12028230.html 访问时间 2023/3/27.✅

Powershell脚本的4种执行权限介绍,Windows默认不允许任何脚本运行,我们可以使用"Set-ExecutionPolicy"cmdlet来改变的PowerShell环境,共有**4种运行权限**：

　　**Restricted**——默认的设置， 不允许任何script运行
　　**AllSigned**——只能运行经过数字证书签名的script
　　**RemoteSigned**——运行本地的script不需要数字签名，但是运行从网络上下载的script就必须要有数字签名
　　**Unrestricted**——允许所有的script运行

(2) Powershell无法执行脚本问题解决方案_Alexhirchi的博客-CSDN博客. https://blog.csdn.net/weixin_43669045/article/details/104269284 访问时间 2023/3/27.
(3) WindowsPowerShell 出现无法识别cmdlet、函数、脚本等错误_阿阿阿黄的博客-CSDN博客. https://blog.csdn.net/mblhq/article/details/53968138 访问时间 2023/3/27.

检查了一下没啥问题：

![image-20230327164259271](Knowledge%20I%20learned%20by%20chance.assets/image-20230327164259271.png)

我又想检查一下set path指令是否有效，所以我**删除了系统里设置的path变量**，**在Powershell里输入set path指令**，<font color='orange'>**发现居然无法调用vlib指令**</font>，说明set path并没有正确地加入变量？？？

![image-20230328103517376](Knowledge%20I%20learned%20by%20chance.assets/image-20230328103517376.png)

然后在cmd里面试了试，发现**cmd里是可以运行的**，所以**set path实际上是cmd专用的语法**？？？

![image-20230328103851343](Knowledge%20I%20learned%20by%20chance.assets/image-20230328103851343.png)

在PowerShell中**查询get path指令**，发现根本找不到（乐）

![image-20230328105109252](Knowledge%20I%20learned%20by%20chance.assets/image-20230328105109252.png)

查询path变量：

![image-20230328105149765](Knowledge%20I%20learned%20by%20chance.assets/image-20230328105149765.png)

师兄让我又**重装了一个Modelsim10.1a**，结果依然是这个问题

另外，重启时还弹了个弹窗，不知道会不会有影响

![image-20230328113805485](Knowledge%20I%20learned%20by%20chance.assets/image-20230328113805485.png)

于是我**将代码一行一行输入到PowerShell中**，发现**绝大多数都是可以跑过的**

最后我**新建了一个txt手打了一遍原来的代码**，不可思议的事情发生了，代码通过了，我又开始怀疑是编码问题，于是我**复制了原来的代码到新建的bat里**发现也通过了！至此，我<font color='red'>**完全排除了编码的问题**</font>

我对比了一下我的新代码与原代码的区别：

![image-20230329105336893](Knowledge%20I%20learned%20by%20chance.assets/image-20230329105336893.png)

也就是说，<font color='red'>**问题完全在于那个开头的与path有关的代码**</font>！（震惊）

我把原文件的path代码注释掉，果然也通过了（笑）

后面还<font color='orange'>**弹出了一个secureip库的问题**</font>，本来怀疑是vivado的问题，但其实是因为**Modelsim.ini里面有一个关于secureip库的路径设置**，师兄**发给我了一个xilinx_sim_lib的文件夹**解决了这个问题

![image-20230330105520753](Knowledge%20I%20learned%20by%20chance.assets/image-20230330105520753.png)

### *破解相关*

​		***为什么我的modelsim目录有mgls.dll文件在破解时却依旧提示缺少mgls.dll文件呢***

![image-20230329110316230](Knowledge%20I%20learned%20by%20chance.assets/image-20230329110316230.png)

这个error可能是**<font color='red'>因为你在运行patch_dll.bat文件时没有用命令提示符的方式打开，而是直接右键运行</font>**¹²。这样会导致找不到mgls.dll文件，无法生成license文件¹²。你可以尝试以下步骤来解决这个问题：
- 首先确保你的modelsim目录下有mgls.dll或mgls64.dll文件，并且取消它们的只读属性¹²³。
- 然后用文本编辑器打开patch_dll.bat文件，如果你安装的是64位modelsim，将mgls.dll改为mgls64.dll³。
- 接着打开命令提示符，切换到modelsim的安装目录下的win64文件夹，输入patch_dll.bat并回车，等待生成license.txt文件¹²³。
- 最后在环境变量中添加MGLS_LICENSE_FILE变量，值为license.txt文件的完整路径¹²³。

源: 与必应的对话， 2023/3/29(1) ModelSim安装时找不到mgls.dll或mgls64.dll问题_找不到mgls.dll .... https://blog.csdn.net/Meloneating/article/details/113725222 访问时间 2023/3/29.✅

​		**在命令行里调用而不要右键管理员运行**

(2) Modelsim 10以上版本在WIN10下找不到LICENSE的解决办法. https://blog.csdn.net/vistayi/article/details/102966383 访问时间 2023/3/29.
(3) 解决modelsim破解在win10下运行patch失败-百度经验. https://jingyan.baidu.com/article/8cdccae9258b1c315413cdf2.html 访问时间 2023/3/29.

### *检查Modelsim代码的工具*

​		***有没有可以自动检查modelsim代码格式的工具？***

![image-20230328171942630](Knowledge%20I%20learned%20by%20chance.assets/image-20230328171942630.png)

您好，这是必应。我尝试了搜索您的消息，找到了一些可能有用的信息。

根据搜索结果，我发现了以下内容：

- modelsim代码格式指的是modelsim中用于编写和仿真硬件描述语言（HDL）的代码的风格和规范，例如缩进、注释、命名等。¹
- modelsim代码格式的检查和整理可以提高代码的可读性和可维护性，也可以避免一些潜在的错误和问题。¹
- 有一些工具可以用来检查和整理modelsim代码格式，例如：¹²³
  - nLint：一个集成于Debussy或Verdi调试平台的设计规则检查工具，可以对HDL代码的语法和语义的正确性进行分析，并提供一些修改建议。
  - Verilog HDL代码分析及整理软件：一个独立的软件，可以对Verilog代码进行格式化、注释、重命名等操作，也可以生成模块实例化和测试平台。
  - Vscode + modelsim：一个基于Vscode编辑器和modelsim仿真器的环境搭建，可以利用Vscode中的插件进行语法高亮、自动补全、语法检查等功能，也可以利用modelsim中的vlog命令进行编译。

请问这些内容对您有帮助吗？如果不是，请告诉我您想要了解什么。

源: 与必应的对话， 2023/3/28(1) 【干货】推荐一款FPGA仿真调试鸟枪换炮的工具 .... https://cloud.tencent.com/developer/article/1528868 访问时间 2023/3/28.✅

​		***Debussy***

​		***Simvision***

(2) Vscode + modelsim 环境搭建_zhuanshulz的博客-CSDN博客. https://blog.csdn.net/u014139753/article/details/110920047 访问时间 2023/3/28.
(3) 如何在vscode上配合modelsim写VHDL代码_vscode编写vhdl_Yetjj的 .... https://blog.csdn.net/Yetjj/article/details/117457896 访问时间 2023/3/28.

### *Modelsim与Debussy的联动*

***我看他们通过在modelsim.ini里将Veriuser = veriuser.sl改为Veriuser = novas.dll实现Modelsim和Debussy的联动就可以使用$fsdbDumpfile指令了，是因为Debussy里集成了Verdi语法吗***

![image-20230330161442688](Knowledge%20I%20learned%20by%20chance.assets/image-20230330161442688.png)

不是的。Debussy是一个专业的波形调试工具，它可以和Modelsim进行联合仿真，**<font color='red'>通过修改modelsim.ini文件，让Modelsim加载Verdi的库文件¹。这样，Modelsim就可以执行<u>$fsdbDumpfile指令</u>，并生成fsdb文件供Debussy查看²</font>**。Debussy并没有集成Verdi的语法，而是**<font color='red'>通过PLI接口实现了和Modelsim的通信</font>**³。Debussy是Verdi的旧版本，Verdi是Debussy的升级版，两者功能大同小异²³。

源: 与必应的对话， 2023/3/30(1) 【干货】推荐一款FPGA仿真调试鸟枪换炮的工具 .... https://cloud.tencent.com/developer/article/1528868 访问时间 2023/3/30.
(2) Novas Verdi、Debussy ，Synopsys VCS，Candence NC-Verilog，Mentor .... https://blog.csdn.net/wordwarwordwar/article/details/80207303 访问时间 2023/3/30.
(3) vcs+verdi/Debussy_时光-易逝的博客-CSDN博客. https://blog.csdn.net/u011329967/article/details/106752304 访问时间 2023/3/30.

***PLI接口是什么东西***

PLI接口是编程语言接口（Programming Language Interface）的缩写，它是一种软件接口，可以让C语言和Verilog语言相互调用和交互¹。PLI接口有三个版本，分别是TF接口、ACC接口和VPI接口¹²。TF接口是最早的版本，它主要用于编写用户自定义的系统任务和函数，以扩展Verilog语言的功能¹。ACC接口是第二代版本，它主要用于访问和修改Verilog描述的多种对象¹。VPI接口是最新的版本，它是TF和ACC接口功能的合集，定义在vpi_user.h中²。VPI接口比PLI接口更精简和规范，但是结构更复杂，支持性不太友好²。

源: 与必应的对话， 2023/3/30(1) Verilog Procedural Interface - Wikipedia. https://en.wikipedia.org/wiki/Verilog_Procedural_Interface 访问时间 2023/3/30.
(2) 8.1 Verilog PLI 简介 | 菜鸟教程. https://www.runoob.com/w3cnote/verilog2-pli-intro.html 访问时间 2023/3/30.✅

​		**介绍了PLI的几个阶段，同时也讲解了一个Verilog与C联动的例子**

***请问modelsim.ini中有哪些PLI接口呢***

modelsim.ini是ModelSim仿真器的配置文件，它可以用来指定一些仿真选项和PLI接口¹。PLI接口是一种软件接口，可以让C语言和Verilog语言相互调用和交互²。在modelsim.ini中，有以下几个与PLI接口相关的条目：

- **<font color='red'>Veriuser</font>**：指定用户自定义的系统任务和函数的动态链接库文件，一般是以.dll或者.sl为后缀的文件¹²。例如，Veriuser = novas.dll表示使用novas.dll文件作为用户自定义的系统任务和函数的库文件。
- VsimStartup：指定在启动vsim时要执行的Tcl脚本文件，可以用来加载一些PLI接口的库文件或者设置一些PLI接口的参数¹。例如，VsimStartup = vsim_startup.tcl表示在启动vsim时要执行vsim_startup.tcl脚本文件。
- Pli：指定一些PLI接口的选项，包括以下几个子条目¹：
  - LoadVpi：指定要加载的VPI（Verilog Procedural Interface）库文件，可以有多个LoadVpi条目，每个条目对应一个库文件。例如，LoadVpi = test_pli.dll表示加载test_pli.dll作为VPI库文件。
  - LoadTf：指定要加载的TF（Task/Function）库文件，可以有多个LoadTf条目，每个条目对应一个库文件。例如，LoadTf = test_tf.sl表示加载test_tf.sl作为TF库文件。
  - LoadAcc：指定要加载的ACC（Access）库文件，可以有多个LoadAcc条目，每个条目对应一个库文件。例如，LoadAcc = test_acc.sl表示加载test_acc.sl作为ACC库文件。
  - VpiTrace：指定是否打开VPI调试信息的输出，取值为0或者1。例如，VpiTrace = 1表示打开VPI调试信息的输出。
  - TfTrace：指定是否打开TF调试信息的输出，取值为0或者1。例如，TfTrace = 1表示打开TF调试信息的输出。
  - AccTrace：指定是否打开ACC调试信息的输出，取值为0或者1。例如，AccTrace = 1表示打开ACC调试信息的输出。

希望这些信息能够对你有所帮助。😊

源: 与必应的对话， 2023/3/31(1) [verilog]如何在modelsim中使用PLI功能_modelsim pli_adream307的 .... https://blog.csdn.net/adream307/article/details/16903143 访问时间 2023/3/31.
(2) The ModelSim commands you need to know - VHDLwhiz. https://vhdlwhiz.com/the-modelsim-commands-you-need-to-know/ 访问时间 2023/3/31.
(3) Failed to load PLI object file libcocotbvpi_modelsim.dll #1995. https://github.com/cocotb/cocotb/issues/1995 访问时间 2023/3/31.

## *Verdi*

### *Verdi语法*

***有没有什么介绍Verdi语法比较好的中文网站***

我在网上搜索了一些关于Verdi语法的中文网站，以下是一些可能有用的资源：

- Verdi 基础教程_沧海一升的博客-CSDN博客¹，这篇博客介绍了Verdi的基本功能和使用方法，包括环境配置、nTrace、nSchema、nState、nWare等工具的使用。
- Verdi使用总结 – Wenhui's Rotten Pen²，这篇文章总结了Verdi的一些常用技巧和注意事项，包括设置符号库、FSDB文件处理、导入设计、查看原理图、添加波形等。
- Verdi基础知识整理_verdi 参数_254、小小黑的博客-CSDN博客³，这篇博客整理了Verdi的一些基础知识和参数，包括生成FSDB波形、查看FSDB波形、追踪RTL代码等。
- Verdi命令行调用选项用法_uvm_verdi_trace_Alfred.HOO的博客-CSDN博客⁴，这篇博客介绍了Verdi命令行调用的一些选项和用法，包括指定资源文件、语言类型、源文件列表等。

希望这些网站能够对你有所帮助。😊

源: 与必应的对话， 2023/3/31(1) Verdi 基础教程_沧海一升的博客-CSDN博客. https://blog.csdn.net/qq_21842097/article/details/116144372 访问时间 2023/3/31.
(2) Verdi使用总结 – Wenhui's Rotten Pen. https://www.wenhui.space/docs/07-ic-verify/tools/verdi_userguide/ 访问时间 2023/3/31.
(3) Verdi基础知识整理_verdi 参数_254、小小黑的博客-CSDN博客. https://blog.csdn.net/immeatea_aun/article/details/80961258 访问时间 2023/3/31.
(4) Verdi命令行调用选项用法_uvm_verdi_trace_Alfred.HOO的博客 .... https://blog.csdn.net/Michael177/article/details/124639341 访问时间 2023/3/31.



## *常用工具的分类*

***modelsim、vivado和VCS、Debussy、Verdi这些软件在功能上有什么区别？***

这些软件在功能上有一些区别，大致可以分为以下几类：

- **Modelsim、VCS和NC-Verilog**是**仿真工具**，它们可以**执行HDL代码的编译、仿真和波形显示**，但是它们的效率和兼容性有所不同。Modelsim是最常用的仿真工具，<font color='red'>**支持Windows和Linux环境**</font>，但是它的仿真结果**<font color='red'>可能不被芯片设计认可</font>**¹²。VCS和NC-Verilog是**<font color='red'>专业的芯片设计用的仿真工具</font>**，它们**<font color='red'>只支持Linux环境</font>**，但是它们的**<font color='red'>仿真速度和准确性更高</font>**¹²。

- **Vivado和Quartus**是**FPGA综合工具**，它们可以**将HDL代码转换为FPGA的网表，并进行布局布线、时序分析和下载**等操作，但是它们的综合效果和支持的FPGA型号有所不同。Vivado是**<font color='cornflowerblue'>Xilinx公司</font>**的FPGA综合工具，**<font color='red'>支持Windows和Linux环境</font>**，主要针对7系列以上的FPGA³。Quartus是**<font color='cornflowerblue'>Intel公司</font>**的FPGA综合工具，**<font color='red'>支持Windows和Linux环境</font>**，主要针对Cyclone、Stratix和Arria等系列的FPGA⁴。

- **Debussy和Verdi**是**调试工具**，它们可以**在HDL源代码、原理图、波形、状态图等之间进行追踪、分析和定位问题**，但是它们的版本和平台有所不同。Debussy和Verdi都是<font color='cornflowerblue'>**NOVAS Software, Inc（思源科技）**</font>开发的调试工具，Debussy是Verdi的旧版本，<font color='red'>**Verdi是Debussy的升级版**</font>，两者功能大同小异² 。**<font color='red'>Debussy支持Windows环境，而Verdi只支持Linux环境</font>**² 。

***所以他们都是ic数字设计需要的工具对吗***

不完全是。Modelsim、VCS、NC-Verilog、Debussy和Verdi都是IC数字设计需要的工具，它们可以用来验证和调试HDL代码的功能和性能。但是Vivado和Quartus是FPGA综合工具，它们主要用来将HDL代码转换为FPGA的网表，并进行布局布线、时序分析和下载等操作，它们不适用于IC数字设计，因为IC数字设计需要另外的综合工具，如Design Compiler、Genus等。

源: 与必应的对话， 2023/3/30(1) 单纯做fpga仿真（非数字IC），请问VCS相比于modelsim有 .... https://www.zhihu.com/question/270518986 访问时间 2023/3/30.
(2) 【干货】推荐一款FPGA仿真调试鸟枪换炮的工具 .... https://cloud.tencent.com/developer/article/1528868 访问时间 2023/3/30.
(3) VCS与Verdi的联合仿真 - 腾讯云开发者社区-腾讯云. https://cloud.tencent.com/developer/article/1669477 访问时间 2023/3/30.
(4) VCS与Verdi工具初体验 - 知乎. https://zhuanlan.zhihu.com/p/274783452 访问时间 2023/3/30.

## *用户变量和系统变量*

​		***请问环境变量中的用户变量和系统变量有什么区别***

![image-20230329110803272](Knowledge%20I%20learned%20by%20chance.assets/image-20230329110803272.png)

用户变量和系统变量是Windows系统中存在的两种环境变量¹²³。它们的区别有以下几点：
- **用户变量只对当前用户有效，系统变量对所有用户有效**¹²³。
- **用户变量和系统变量中可以存在重名的变量，但是用户变量会覆盖系统变量**²³。
- **用户变量和系统变量都不区分变量名的大小写，如Path和PATH并没有区别**¹²。
- Windows系统在执行用户命令时，若用户未给出文件的绝对路径，则首先在当前目录下寻找相应的可执行文件、批处理文件等；若找不到，再依次在系统变量的PATH保存的这些路径中寻找相应的可执行程序文件；如果还找不到再在用户变量的PATH路径中寻找¹。

源: 与必应的对话， 2023/3/29(1) windows系统变量和用户变量的区别？ - 知乎. https://zhuanlan.zhihu.com/p/480557922 访问时间 2023/3/29.
(2) windows 用户变量和系统变量的区别_阳光的颜色的博客 .... https://blog.csdn.net/sxhlovehmm/article/details/44274633 访问时间 2023/3/29.
(3) Windows 10 / 11 环境变量 (用户变量与系统变量)_Yongqiang .... https://blog.csdn.net/chengyq116/article/details/105900122 访问时间 2023/3/29.

## *Git*

### ***安装相关***

***安装git时提示Choosing the SSh executable，use bundled OpenSSH和Use external OpenSSH有什么区别***

![image-20230331104307646](Knowledge%20I%20learned%20by%20chance.assets/image-20230331104307646.png)

这个问题的答案可以在搜索结果中找到。根据¹和²，Choosing the SSH executable是选择SSH可执行文件，用于Git和远程仓库之间的安全通信。有两个选项：

- Use bundled OpenSSH: 这个选项使用Git自带的ssh.exe程序，不需要额外安装或配置。
- Use external OpenSSH: 这个选项使用系统中已经安装的ssh.exe程序，需要保证其版本和路径正确。这个选项是新的，可能有一些兼容性问题。

一般来说，推荐使用第一个选项，除非你有特殊的需求或偏好。

源: 与必应的对话， 2023/3/31(1) Git安装全教程（Win11） - 知乎. https://zhuanlan.zhihu.com/p/607970211 访问时间 2023/3/31.
(2) Git 详细安装教程（详解 Git 安装过程的每一个步骤 .... https://blog.csdn.net/mukes/article/details/115693833 访问时间 2023/3/31.
(3) git安装 - 掘金. https://juejin.cn/post/7122763383836770335 访问时间 2023/3/31.

***这个SSH是什么东西，有什么用呢***

SSH是一种网络安全协议，通过加密和认证机制实现安全的访问和文件传输等业务¹。SSH可以用于远程登录、端口转发、动态代理等场景，提高网络通信的安全性和效率。SSH由服务器和客户端组成，使用公钥和私钥进行身份验证和数据加密²。SSH的默认端口号是22，可以根据需要修改³。

源: 与必应的对话， 2023/3/31(1) 【科普】SSH都不懂，还搞什么网络 - 知乎. https://zhuanlan.zhihu.com/p/323322650 访问时间 2023/3/31.
(2) 什么是SSH？SSH是如何工作的？ - 华为. https://info.support.huawei.com/info-finder/encyclopedia/zh/SSH.html 访问时间 2023/3/31.
(3) SSH是啥？？ - 知乎. https://zhuanlan.zhihu.com/p/472357664 访问时间 2023/3/31.

***Choosing HTTPS transport backend里Use the OpenSSL和Use the native Windows secure Channel library有什么区别***

![image-20230331104326679](Knowledge%20I%20learned%20by%20chance.assets/image-20230331104326679.png)

这个问题的答案可以在搜索结果中找到。根据¹和²，Choosing HTTPS transport backend是选择HTTPS传输后端，用于Git和远程仓库之间的安全通信。有两个选项：

- Use the OpenSSL library: 这个选项使用OpenSSL库，服务器证书将使用ca-bundle.crt文件进行验证。
- Use the native Windows Secure Channel library: 这个选项使用Windows自带的Secure Channel库，可以利用Windows Credential Store进行企业级的证书管理。

一般来说，如果你在一个有企业管理的证书的组织中使用Git，那么你需要使用Secure Channel。如果你只是访问公开的仓库（如GitHub）或者你的组织没有自己管理的证书，那么你可以使用任意一个选项。

源: 与必应的对话， 2023/3/31(1) What's the difference between OpenSSL and the native windows Secure .... https://stackoverflow.com/questions/62456484/whats-the-difference-between-openssl-and-the-native-windows-secure-channel-libr 访问时间 2023/3/31.
(2) Switch to "Native Windows Secure Channel library" from "OpenSSL library .... https://stackoverflow.com/questions/45742607/switch-to-native-windows-secure-channel-library-from-openssl-library-on-wind 访问时间 2023/3/31.
(3) git中文安装教程_git中文包安装_Petrus1021的博客-CSDN博客. https://blog.csdn.net/sishen47k/article/details/80211002 访问时间 2023/3/31.
(4) Git安装教程 - 简书. https://www.jianshu.com/p/43aa7e282716 访问时间 2023/3/31.

***选择SSH程序和这个选择SSL/TLS library有什么区别呢***

这个问题的答案可以在搜索结果中找到。根据¹和²，选择SSH程序是选择SSH可执行文件，用于Git和远程仓库之间的安全登录。有两个选项：

- Use OpenSSH: 这个选项使用Git自带的ssh.exe程序，不需要额外安装或配置。
- Use (Tortoise)Plink: 这个选项使用系统中已经安装的plink.exe程序，需要保证其版本和路径正确。这个选项可以与PuTTY或TortoiseGit配合使用。

选择SSL/TLS library是选择HTTPS传输后端，用于Git和远程仓库之间的安全通信。有两个选项：

- Use the OpenSSL library: 这个选项使用OpenSSL库，服务器证书将使用ca-bundle.crt文件进行验证。
- Use the native Windows Secure Channel library: 这个选项使用Windows自带的Secure Channel库，可以利用Windows Credential Store进行企业级的证书管理。

一般来说，如果你在一个有企业管理的证书的组织中使用Git，那么你需要使用Secure Channel。如果你只是访问公开的仓库（如GitHub）或者你的组织没有自己管理的证书，那么你可以使用任意一个选项。

源: 与必应的对话， 2023/3/31(1) SSL与SSH的区别 - 知乎. https://zhuanlan.zhihu.com/p/138679729 访问时间 2023/3/31.
(2) SSL，HTTPS，TLS三者的区别 - 知乎. https://zhuanlan.zhihu.com/p/158711125 访问时间 2023/3/31.
(3) SSL和SSH有什么区别_沃通WoTrus的博客-CSDN博客. https://blog.csdn.net/WoTrusCA/article/details/109217153 访问时间 2023/3/31.

***Git安装中Configuring the line ending conversions该怎么选***

这个问题的答案可以在搜索结果中找到。根据¹和²，Configuring the line ending conversions是配置Git如何处理行结束符。行结束符是每次按回车键时插入的一个不可见字符，不同的操作系统处理行结束符的方式不同。如果你在Windows上使用Git，而你的协作者在macOS或Linux上使用Git，可能会出现行结束符不一致的问题。你可以配置Git来自动处理行结束符，以便与使用不同操作系统的人员有效地协作。有三个选项：

- Checkout Windows-style, commit Unix-style line endings: 这个选项会在检出文件时将行结束符转换为CRLF（回车换行），在提交文件时将行结束符转换为LF（换行）。这是Windows上的推荐选项，可以保持跨平台的兼容性。
- Checkout as-is, commit Unix-style line endings: 这个选项会在检出文件时保留原始的行结束符，不做任何转换，在提交文件时将行结束符转换为LF（换行）。这是macOS或Linux上的推荐选项，可以避免不必要的转换。
- Checkout as-is, commit as-is: 这个选项会完全忽略行结束符的问题，不做任何转换。这是一个危险的选项，除非你知道自己在做什么，否则不要使用它。

源: 与必应的对话， 2023/3/31(1) Configuring Git to handle line endings - GitHub Docs. https://docs.github.com/en/get-started/getting-started-with-git/configuring-git-to-handle-line-endings 访问时间 2023/3/31.
(2) 配置 Git 处理行结束符 - GitHub 文档. https://docs.github.com/zh/get-started/getting-started-with-git/configuring-git-to-handle-line-endings 访问时间 2023/3/31.
(3) Git安装配置教程_操吴戈兮被犀甲的博客-CSDN博客. https://blog.csdn.net/u013295518/article/details/78746007 访问时间 2023/3/31.

***Configuring the terminal emulator to use with Git Bash怎么选***

![image-20230331105451898](Knowledge%20I%20learned%20by%20chance.assets/image-20230331105451898.png)

这个问题的答案可以在搜索结果中找到。根据¹和²，Configuring the terminal emulator to use with Git Bash是选择终端模拟器来使用Git Bash。Git Bash是一个为Windows环境提供的模拟Git命令行体验的应用程序。有两个选项：

- Use MinTTY (the default terminal of MSYS2): 这个选项使用MinTTY程序，它是一个轻量级的终端模拟器，具有可调整窗口大小和其他有用的可配置选项。这是默认的和推荐的选项，除非你有特殊的需求或偏好。
- Use Windows' default console window: 这个选项使用Windows自带的控制台窗口（cmd.exe），它是一个基本的终端模拟器，具有有限的功能和选项。这个选项可以简化运行交互式程序，但可能会遇到一些兼容性问题。

源: 与必应的对话， 2023/3/31(1) Git setup - Terminal Emulator for Git Bash - Stack Overflow. https://stackoverflow.com/questions/36905283/git-setup-terminal-emulator-for-git-bash 访问时间 2023/3/31.
(2) How to Install Git and Git Bash on Windows - MUO. https://www.makeuseof.com/install-git-git-bash-windows/ 访问时间 2023/3/31.
(3) Access to a Linux-like terminal on Windows via Git Bash. https://gist.github.com/bhubr/00c6e39e72231cf091a17772d73e6fb3 访问时间 2023/3/31.

***Choose the default behavior of git pull 怎么选***

这个问题的答案可以在搜索结果中找到。根据¹和²，Choose the default behavior of git pull是选择git pull的默认行为。git pull是一个命令，用于从远程仓库获取最新的版本，并合并到本地分支。有三个选项：

- Default (fast-forward or merge): 这个选项是git pull的标准行为，当可能的时候，会将当前分支快进到获取的分支，否则会创建一个合并提交。这个选项可以保持分支的历史完整，但可能会产生一些不必要的合并提交。
- Rebase: 这个选项会将当前分支的提交重新应用到获取的分支之上，然后将当前分支指向最新的提交。这个选项可以保持分支的历史简洁，但可能会改变提交的顺序和哈希值，造成一些潜在的风险。
- Fast-forward only: 这个选项只会在可以快进的情况下执行git pull，否则会拒绝合并，并提示用户手动解决冲突。这个选项可以避免不必要的合并提交，但可能会阻碍一些常见的工作流程。

源: 与必应的对话， 2023/3/31(1) Default behaviour of 'git pull' - Stack Overflow. https://stackoverflow.com/questions/40739305/default-behaviour-of-git-pull 访问时间 2023/3/31.
(2) How to discover the current default behavior for git pull?. https://stackoverflow.com/questions/63001513/how-to-discover-the-current-default-behavior-for-git-pull 访问时间 2023/3/31.
(3) git安装 - 掘金. https://juejin.cn/post/7122763383836770335 访问时间 2023/3/31.
(4) Three Git Configurations that Should Be the Default - Atomic Spin. https://spin.atomicobject.com/2020/05/05/git-configurations-default/ 访问时间 2023/3/31.

***git pull的三种模式***

![image-20230331111950133](Knowledge%20I%20learned%20by%20chance.assets/image-20230331111950133.png)

***分析一下Default模式、Rebase模式、Only ever fast-forward模式分别有什么优缺点以及应用场景***

Default模式、Rebase模式、Only ever fast-forward模式是git pull的三种合并策略，它们分别有以下优缺点和应用场景：

- Default模式：这是git pull的默认策略，它会在本地仓库和远程仓库的分支有不同的修改时，创建一个合并提交来把两个分支合并。这样**<font color='red'>可以保留两个分支的历史记录</font>**，但也**<font color='red'>会产生额外的合并提交</font>**，可能导致**<font color='red'>历史记录比较复杂和混乱</font>**。这种模式适合在**多人协作**的情况下，需要频繁同步远程仓库的更新。
- Rebase模式：这种策略会先把本地仓库的分支回退到和远程仓库的分支相同的状态，然后把本地仓库的修改重新应用到远程仓库的更新之后。这样可以避免产生额外的合并提交，**保持历史记录的线性和清晰**，但也会改变本地仓库的历史记录，可能导致一些冲突和错误。这种模式适合在**单人开发**或者**需要保持历史记录整洁**的情况下。
- Only ever fast-forward模式：这种策略**<font color='red'>只在本地仓库和远程仓库的分支没有分叉时才能进行合并</font>**，也就是说只有当**<font color='red'>本地仓库的分支落后于远程仓库的分支时才能执行git pull</font>**。这样可以保证历史记录的一致性和简洁性，但也会限制本地仓库的修改，需要先解决冲突再推送到远程仓库。这种模式适合在需要严格控制代码质量和版本管理的情况下。

源: 与必应的对话， 2023/3/31(1) Git Pull vs Git fetch Which one is Preferable? - Stack Overflow. https://stackoverflow.com/questions/44718042/git-pull-vs-git-fetch-which-one-is-preferable 访问时间 2023/3/31.
(2) Git - The Protocols. https://git-scm.com/book/en/v2/Git-on-the-Server-The-Protocols 访问时间 2023/3/31.
(3) Push vs. Pull in GitOps: Is There Really a Difference?. https://thenewstack.io/push-vs-pull-in-gitops-is-there-really-a-difference/ 访问时间 2023/3/31.

***Default模式下本地文件与远程仓库发生冲突是什么情况，能举一个代码的例子吗***

好的，我可以举一个具体的代码的例子来说明。假设你和你的同事都在本地分支master上修改了一个文件，比如index.html。你在文件的第一行添加了一个标题，你的同事在文件的最后一行添加了一个链接。你们的修改如下：

你的本地文件：

```html
<h1>这是一个标题</h1>
<p>这是一个段落</p>
```

你的同事的远程文件：

```html
<p>这是一个段落</p>
<a href="https://www.baidu.com">这是一个链接</a>
```

如果你选择了default模式，在修改了本地的代码后，使用git pull会发生什么呢？首先，git pull会从远程仓库获取最新的代码，并尝试合并到本地分支。但是，因为你们两个都修改了同一个文件，而且修改的位置有重叠，所以git pull会发现有冲突，无法自动合并。git pull会创建一个新的提交，把两边的修改都合并进去，但是会在冲突的地方添加一些标记，让你手动解决冲突。你的本地文件会变成这样：

```html
<<<<<<< HEAD
<h1>这是一个标题</h1>
=======
>>>>>>> 4e2b407f501b68f8588aa645acafffa0224b9b78
<p>这是一个段落</p>
<a href="https://www.baidu.com">这是一个链接</a>
```

你可以看到，git pull在冲突的地方添加了一些标记，用<<<<<<< HEAD和=======分隔了本地分支和远程分支的修改，用>>>>>>>和一串哈希值标识了远程分支的最新提交。你需要根据自己的意图，选择保留哪些修改，删除哪些修改，以及删除所有的标记。比如，如果你想保留两边的修改，并且把标题放在段落之前，你可以把文件改成这样：

```html
<h1>这是一个标题</h1>
<p>这是一个段落</p>
<a href="https://www.baidu.com">这是一个链接</a>
```

然后，你需要执行git add和git commit命令，完成合并提交。你可以用git log命令查看本地分支的提交历史，你会看到一个新的合并提交，它有两个父提交，分别是本地分支和远程分支的最新提交。你可以用git show命令查看合并提交的内容，你会看到合并的结果。最后，你可以执行git push命令，将本地分支推送到远程仓库。

源: 与必应的对话， 2023/3/31(1) Git merge conflicts | Atlassian Git Tutorial. https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts 访问时间 2023/3/31.
(2) git pull and resolve conflicts - Stack Overflow. https://stackoverflow.com/questions/35025587/git-pull-and-resolve-conflicts 访问时间 2023/3/31.
(3) How to Resolve Merge Conflicts in Git – A Practical Guide with Examples. https://www.freecodecamp.org/news/resolve-merge-conflicts-in-git-a-practical-guide/ 访问时间 2023/3/31.


***Git安装时choose a credential helper怎么选***

![image-20230331173127296](Knowledge%20I%20learned%20by%20chance.assets/image-20230331173127296.png)

Git安装时choose a credential helper是用来选择Git如何存储和获取远程仓库的用户名和密码的选项¹。不同的helper有不同的优缺点，比如：

- 默认模式：每次连接都需要输入用户名和密码，安全但麻烦
- cache模式：将凭证缓存在内存中一段时间，不会保存在磁盘上，但会在一定时间后过期
- store模式：将凭证永久保存在磁盘上一个明文文件中，方便但不安全
- osxkeychain模式：将凭证保存在Mac系统的安全钥匙串中，安全且方便，但只适用于Mac系统
- **Git Credential Manager for Windows**：类似于osxkeychain模式，但使用Windows凭证存储，只适用于Windows系统

你可以根据你的需求和偏好来选择一个合适的helper。一般来说，如果你使用的是HTTPS协议连接远程仓库，并且想要避免重复输入凭证，你可以选择cache或store模式。如果你使用的是SSH协议，并且有一个没有密码的密钥，你可以不需要helper。如果你想要更高的安全性和便利性，你可以选择osxkeychain或Git Credential Manager for Windows模式，前提是你使用的是相应的操作系统。

源: 与必应的对话， 2023/3/31(1) Git - Credential Storage. https://git-scm.com/book/be/v2/Git-Tools-Credential-Storage 访问时间 2023/3/31.
(2) Custom Git Credential Helper - Stack Overflow. https://stackoverflow.com/questions/59645494/custom-git-credential-helper 访问时间 2023/3/31.
(3) Storing Git Credentials with Git Credential Helper - Medium. https://techexpertise.medium.com/storing-git-credentials-with-git-credential-helper-33d22a6b5ce7 访问时间 2023/3/31.

***Git安装时Configuring extra options怎么选***

![image-20230331173618083](Knowledge%20I%20learned%20by%20chance.assets/image-20230331173618083.png)

Git安装时Configuring extra options是用来选择Git的一些额外的配置选项的，比如：

- Enable file system caching：启用文件系统缓存，可以提高Git的性能
- Enable Git Credential Manager：启用Git凭证管理器，可以方便地存储和获取远程仓库的用户名和密码
- Enable symbolic links：启用符号链接，可以在Windows系统上使用类似于Linux系统的软链接功能

你可以根据你的需求和偏好来选择是否勾选这些选项。一般来说，如果你想要提高Git的速度和便利性，你可以选择勾选前两个选项。如果你想要使用符号链接功能，你可以选择勾选最后一个选项，但是需要注意，这可能需要你以管理员身份运行Git Bash或者开启Windows的开发者模式¹。

源: 与必应的对话， 2023/3/31(1) Git Guides - install git · GitHub. https://github.com/git-guides/install-git 访问时间 2023/3/31.
(2) Install and set up Git - Azure DevOps | Microsoft Learn. https://learn.microsoft.com/en-us/devops/develop/git/install-and-set-up-git 访问时间 2023/3/31.
(3) Git - Installing Git. https://git-scm.com/book/en/v2/Getting-Started-Installing-Git 访问时间 2023/3/31.

### *Sourcetree相关*

***我在git bash上执行ssh -t git@github.com遇到了PTY allocation request failed on channel 0的问题，我是直接登录的github网站（不存在服务器相关的问题），并且我也写了一个config并设置了环境变量SSH_CONFIG_FILE指向它，但是依旧还是会出现这个问题，就算设置了config文件为只读（SSH可能忽略掉非只读文件）也不行，请问还可能是什么原因吗***

非常搞笑的一个原因，在Bing回答了我一堆有的没的以后我去CSDN自己逛了一下，结果发现是**<font color='red'>-t需要大写</font>**，也就是说**<font color='orange'>Bing对这种大小写问题不敏感</font>**（最起码当前是的）

[(10条消息) 本地git连接github时：PTY allocation request failed on channel 0_git pty allocation request failed on channel 0_一个新手^_^的博客-CSDN博客](https://blog.csdn.net/qq_26245011/article/details/97136392?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2~default~CTRLIST~Rate-1-97136392-blog-79796283.235^v27^pc_relevant_multi_platform_whitelistv3&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2~default~CTRLIST~Rate-1-97136392-blog-79796283.235^v27^pc_relevant_multi_platform_whitelistv3&utm_relevant_index=1)

***使用Plink遇到验证问题，但换成OpenSSH就没有***

![image-20230406172622867](Knowledge%20I%20learned%20by%20chance.assets/image-20230406172622867.png)



***From Bing***：你好，这可能是因为你使用Plink时，没有将服务器的主机密钥缓存到注册表中¹²。当你第一次使用Plink连接到一个新的主机时，它会提示你是否信任这个主机，并询问你是否要将主机密钥添加到PuTTY的缓存中¹²。如果你选择y，那么主机密钥就会被缓存到注册表中，以后再连接到这个主机就不会再出现这个提示¹²。如果你选择n，那么主机密钥就不会被缓存，每次连接到这个主机都会出现这个提示¹²。

而使用OpenSSH时，可能是因为你已经在之前的操作中接受过服务器的主机密钥，并将其保存在了.known_hosts文件中³。所以当你再次使用OpenSSH连接到这个主机时，它会自动检查主机密钥是否匹配，而不会再提示你是否信任这个主机³。

希望这些信息对你有帮助。😊

源: 与必应的对话， 2023/4/6(1) Auto-storing server host key in cache with plink. https://serverfault.com/questions/420526/auto-storing-server-host-key-in-cache-with-plink 访问时间 2023/4/6.
(2) Plink SSH Host key -> Windows Registry Entry - Stack Overflow. https://stackoverflow.com/questions/42094333/plink-ssh-host-key-windows-registry-entry 访问时间 2023/4/6.
(3) plink.exe bypass Strict Host Key Checking - Stack Overflow. https://stackoverflow.com/questions/67157098/plink-exe-bypass-strict-host-key-checking 访问时间 2023/4/6.

没太弄懂，反正**<font color='red'>改成OpenSSH就跑通了</font>**，它认为是**<font color='orange'>.known_hosts文件的问题</font>**

***我自己的Sourcetree上的这个“立即推送变更到origin/master”是灰色的***

<img src="Knowledge%20I%20learned%20by%20chance.assets/202304101540203.png" alt="img"  />

![img](Knowledge%20I%20learned%20by%20chance.assets/202304101540278.png)

## *PicGo*

***用Typora+PicGo上传图片时出现404错误代码怎么办？***

![在这里插入图片描述](Knowledge%20I%20learned%20by%20chance.assets/202304101541805.png)

大概率是因为**<font color='red'>仓库命名有问题</font>**导致的

![image-20230410164925911](Knowledge%20I%20learned%20by%20chance.assets/202304101649022.png)

注意图片的链接必须是**<font color='red'>仓库网页链接所显示的格式</font>**

### *Gitee防盗链*

Gitee在2022年3月25日左右添加了防盗链，导致<u>所有Gitee图床的图片在第三方网站访问时会变成Gitee图标</u>，只要**<font color='orange'>将请求头中referer隐藏</font>**即可，但是这样依旧很麻烦所以还是推荐使用其他的图床（Gitee官方也是这么说的，希望我们使用自己的服务器或者其他的图床网站）

# *Life*

## *PayPal*

### *绑卡相关*

***绑卡以后验证时提示：“您的银联卡已关联到您的账户，但发卡机构无法验证您的信息。如需有关卡的帮助，请联系发卡机构。”***

​		[为什么paypal无法认证？ - 知乎 (zhihu.com)](https://www.zhihu.com/question/433119096/answer/2787861304?utm_id=0)

​		解决办法：（以建行为例）开通网银便携支付客户，然后取消绑卡再重新绑定即可，猜测是因为需要开通网银来开启跨平台的小额支付能力

### *Nintendo相关*

​		首先，目前只有日区能用国区的PayPal，其次绑定PayPal时也需要PayPal的银行卡验证通过才行，不然会提示出错

​		另外，在参加优惠活动时记得在<font color='red'>**右上角设置**</font>的**<font color='red'>付款</font>**里找到<font color='red'>**付款方式**</font>

![image-20230329170727608](Knowledge%20I%20learned%20by%20chance.assets/image-20230329170727608.png)

![image-20230329170846820](Knowledge%20I%20learned%20by%20chance.assets/image-20230329170846820.png)

并将**<font color='red'>余额优先</font>**取消，点击<font color='red'>**查看兑换选项**</font>

![image-20230329170904253](Knowledge%20I%20learned%20by%20chance.assets/image-20230329170904253.png)

将**<font color='red'>汇率改为银联</font>**即可

### *风控相关*

​		使用vpn登陆PayPal账户有一定几率被风控检测从而显示“无法认证您为本人”

有以下几种处理方法：

​		**①写邮件给官方（亲测有效）**

​		**国区邮箱：cnsupport@paypal.com**

​		②打电话给官方（但是电话需要动态验证码，动态验证码不登陆看不到，也可能是我没找到，总之很麻烦）

​		③找到“联系我们”中的在线客服，在线客服一般也需要登陆（很蠢），但是我在手机浏览器上偶然找到过不用登陆的人工客服入口，然而进去以后窗口很快被关闭了，之后再想找就找不到了



# *Study*

## *Obsidian*

### *教程相关*

***有什么比较好的Obsidian中文教程***

我在网上搜索了一些关于Obsidian中文教程的资源，以下是一些可能有用的资源：

- Obsidian中文教程 - Obsidian Publish¹，这是一个Obsidian发布服务上的中文教程，包含了Obsidian的基本使用方法、插件介绍、主题推荐、同步方案等内容，还有一些视频资源和案例分享，是一个比较全面和系统的教程。
- 想一小时上手obsidian？这一篇就够了。【玩转Obsidian的第一篇】 - 知乎²，这是一个知乎专栏上的中文教程，主要介绍了Obsidian的原生功能的使用方法，包括界面介绍、文件管理、编辑模式、预览模式、链接和图谱等内容，是一个比较简洁和实用的教程。
- 2021年新教程 - Obsidian中文教程 - Obsidian Publish³，这是一个Obsidian发布服务上的中文教程，主要介绍了2021年Obsidian的新功能和新插件，以及一些使用建议和经验分享，是一个比较更新和针对性的教程。

希望这些资源能够对你有所帮助。😊

源: 与必应的对话， 2023/3/31(1) Obsidian中文教程 - Obsidian Publish. https://publish.obsidian.md/chinesehelp 访问时间 2023/3/31.
(2) 想一小时上手obsidian？这一篇就够了。【玩转Obsidian的 .... https://zhuanlan.zhihu.com/p/428519519 访问时间 2023/3/31.
(3) 2021年新教程 - Obsidian中文教程 - Obsidian Publish. https://publish.obsidian.md/chinesehelp/01+2021%E6%96%B0%E6%95%99%E7%A8%8B/2021%E5%B9%B4%E6%96%B0%E6%95%99%E7%A8%8B 访问时间 2023/3/31.

### *Git和Sourcetree相关*

将本地仓库与远程仓库关联时首先需要初始化，不然会缺少master本地分支

在推送时遇到了只能暂存，推送过去后进入了丢弃里面的情况，想回撤暂存遇到到了下面的情况：

Obsidian里：

![image-20230412155533417](Knowledge%20I%20learned%20by%20chance.assets/image-20230412155533417.png)
Sourcetree里：
![](Knowledge%20I%20learned%20by%20chance.assets/image-20230412155645216.png)

![image-20230412160005918](Knowledge%20I%20learned%20by%20chance.assets/image-20230412160005918.png)
按照菜鸟教程的方法初始化以后总是报错，于是我还是决定使用自建库，然后将笔记存放在自建库里
由于上一次在远程仓库中初始化时留下了一个README.md文件，所以
![[Pasted image 20230412172213.png]]
