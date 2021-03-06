# 电脑端记事本开发设计

## 一、绪论

### 1.1引言

现如今，电脑已经成为了每家每户甚至是每个人手头都必有的一种实用性工具，它改变了人们的生活，大大提高了人们的工作效率。在此基础上，电脑端的记事本应用一直是每台电脑所必备的实用性应用，不管是在台式电脑、笔记本电脑或者平板电脑上，都能看到它的身影。其功能基本有如下几种：文件、编辑、格式、查看、帮助，每个功能下又有多个子功能，为使用者提供了多种编辑上的便利，基本能满足人们记事的需求，特别是快速笔记。正因为它的这些特点，才让它成为每台电脑中必不可少的成分。

### 1.2编写目的

电脑端记事本是每台电脑的标配，有相当大的实用性，方便人们平时的记事之用，尤其是在快速笔记这方面，更是有非常大的作用，基本能满足人们的记事需求，有很大的开发及继续完善开发的意义。

基于记事本的诸多优点，本课程设计针对电脑端的记事本进行开发设计，并在原有基础上进行完善，使它的功能更完善、更人性化及更实用化。

### 1.3 背景

随着人们生活信息化的提高，记事本只拘泥于笔和纸的时代已经一去不复返了，越来越多的电子版记事本进入了人们的生活。但如今的电脑端记事本软件感觉功能不够丰富，缺少一些个性化功能，导致用户体验不是很好，故本课程设计将开发一个加强版的电脑端记事本，来满足用户的需求。

### 1.4 参考资料

[1]. Java从入门到精通（第三版），明日科技，清华大学出版社，2014.8

[2]. 软件工程导论，张海藩，编著，清华大学出版社

[3]. 疯狂java讲义 [J]，李刚，机械工业出版社, 2008. 17-48

[4].Java编程思想［M］.［美］埃克尔著，陈昊鹏译. 机械工业出版社,2004. 5-6

## 二、系统可行性研究

### 2.1系统概述

#### 2.1.1当前系统分析   

当前电脑系统自带的记事本实现的功能有如下几种：文件、编辑、格式、查看、帮助，每个功能下又有多个子功能：

（1）“文件”主菜单中有“新建”、“打开”、“保存”、“另存为”、“页面设置”、“打印”、“退出”这几个子功能。

（2）“编辑”主菜单中有“撤销”、“剪切”、“复制”、“粘贴”、“删除”、“查找”、“查找下一个”、“替换”、“转到”、“全选”、“日期/时间”这几个子功能。

（3）“格式”主菜单中有“自动换行”、“字体”这两个子功能。

（4）“查看”主菜单中有“状态栏”子功能。

（5）“帮助”主菜单中有“查看帮助”、“关于记事本”这两个子功能。

#### 2.1.2目标系统分析   

在实现系统自带笔记本的功能同时，再添加一些个性化功能，例如为记事本添加上行号（这大大提高了我们程序员看代码的方便性），在状态栏添加上当前时间以及字数统计，让用户能够对自己所写的字数一目了然，大大增强了用户体验。

此外，此记事本支持用户自定义背景颜色以及字体颜色，增强了趣味性，用户可以根据自己的喜好选择符合自己的主题。

即实现的功能有：

（1）“文件”主菜单中有“新建”、“打开”、“保存”、“另存为”、“页面设置”、“打印”、“退出”这几个子功能。

（2）“编辑”主菜单中有“撤销”、“剪切”、“复制”、“粘贴”、“删除”、“查找”、“查找下一个”、“替换”、“转到”、“全选”、“日期/时间”这几个子功能。

（3）“格式”主菜单中有“自动换行”、“字体”、“背景颜色”、“字体颜色”这四个子功能。

（4）“查看”主菜单中有“状态栏”子功能。

（5）“帮助”主菜单中有“查看帮助”、“关于记事本”这两个子功能。

### 2.2可行性分析研究   

#### 2.2.1技术可行性

由于计算机技术和互联网技术的发展突飞猛进，计算机的应用深入各行各业。涌现出各种编程语言。本电脑端记事本采用JAVA语言进行开发设计。JAVA语言是一门面向对象的语言，风格接近C、C++语言，但又舍弃了C和C++语言中易引起错误的指针、运算符重载、多重继承等特性，使开发的程序质量更高。由于开发记事本的难度不高，因此通过JAVA语言在Eclipse编译器上就可以实现开发了。

综上，技术可行性满足。

##### 2.2.1.1 Java的基本信息及优势

Java是一种可以撰写跨平台应用程序的面向对象的程序设计语言。Java 技术具有卓越的通用性、高效性、平台移植性和安全性，广泛应用于PC、数据中心、游戏控制台、科学超级计算机、移动电话和互联网，同时拥有全球最大的开发者专业社群。 

与传统程序不同，Sun 公司在推出 Java 之际就将其作为一种开放的技术。全球数以万计的 Java 开发公司被要求所设计的 Java软件必须相互兼容。“Java 语言靠群体的力量而非公司的力量”是Sun公司的口号之一，并获得了广大软件开发商的认同。这与微软公司所倡导的注重精英和封闭式的模式完全不同。 

Sun 公司对 Java 编程语言的解释是：Java 编程语言是个简单、面向对象、分布式、解释性、健壮、安全与系统无关、可移植、高性能、多线程和静态的语言。 

Java 平台是基于 Java 语言的平台。这样的平台非常流行。因此微软公司推出了与之竞争的.NET平台以及模仿Java的C#语言。 

Java是功能完善的通用程序设计语言，可以用来开发可靠的、要求严格的应用程序。

##### 2.2.1.2 Eclipse的基本信息

Eclipse 是一个开放源代码的、基于Java的可扩展开发平台。就其本身而言，它只是一个框架和一组服务，用于通过插件组件构建开发环境。幸运的是，Eclipse 附带了一个标准的插件集，包括Java开发工具（Java Development Kit，JDK）。 

 

 

#### 2.2.2经济可行性

主要分为三方面进行分析，分别是开发的财力物力及时间。

开发的财力物力：

笔记本电脑X 1

其他成本几乎为零，因为该项目开发的难度不大，完成时即刻可以使用，也不需要另外研发硬件设施进行使用，用电脑就行。

开发的时间：从一开始的分析设计到最后的测试维护，时间约为一周就可以，时间成本不大，可行性高。

收益：

​       由于开发这个程序可以更好地满足人们的日常需求，收益还算不错的。

综上，经济可行性满足。

#### 2.2.3操作可行性

本程序采用的是图形化界面方式，记事本的操作不难，一般会使用电脑的人都会操作，只需按照图形界面进行操作，而且每个操作都有相关的快捷键提示，不需要相关的操作指导即可使用，可操作性非常强。

#### 2.2.4社会可行性

根据前期电脑上的记事本的使用情况及普及率来看，记事本的功能是受社会所认可的，人们普遍接受及使用电脑上的记事本，是可以为社会带来利益的。因此，对电脑端的记事本进行再开发完善，发掘它更多的功能并创造出社会价值，可行性是很高的。

 

 

## 三、需求分析

### 3.1系统功能概述

 

![未命名文件](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image002.png)

### 3.2系统功能描述

#### 3.2.1功能图

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image004.png)

#### 3.2.2用例描述

| 用例名称   | 新建                                      |
| ------ | --------------------------------------- |
| 涉及的参与者 | 用户                                      |
| 用例描述   | 在Windows 环境下，新建一个空白txt文档                |
| 前置条件   | 记事本系统可用                                 |
| 正常事件流  | 1．点击开始-所有程序-附件-记事本   2．在记事本系统界面，点击文件-新建 |

 

 

| 用例名称   | 打开                           |
| ------ | ---------------------------- |
| 涉及的参与者 | 用户                           |
| 用例描述   | 在Windows 环境下，新建一个空白txt文档     |
| 前置条件   | 记事本系统可用                      |
| 正常事件流  | 1. 双击打开记事本   2. 左键单击记事本-点击打开 |

 

 

| 用例名称   | 保存或另存为                                   |
| ------ | ---------------------------------------- |
| 涉及的参与者 | 用户                                       |
| 用例描述   | 在Windows 环境下，新建一个空白txt文档                 |
| 前置条件   | 记事本系统可用                                  |
| 正常事件流  | 1. 打开空白记事本，点击文件-保存-再次打开  2.  点击文件-另存为-保存 |

 

 

| 用例名称   | 编辑                                       |
| ------ | ---------------------------------------- |
| 涉及的参与者 | 用户                                       |
| 用例描述   | 在Windows 环境下，新建一个空白txt文档                 |
| 前置条件   | 记事本系统可用                                  |
| 正常事件流  | 1. 在编辑区域输入“软件工程课程设计”  2. 在编辑区域输入“1504”  3.  选中内容“软件工程课程设计”，点击编辑-剪切   4. 点击编辑-撤销   5. 选中内容“软件工程课程设计”，点击编辑-复制  6. 点击编辑-粘贴   7. 选中内容“软件工程课程设计”，点击编辑-删除    8.点击编辑-查找，查找内容“软件工程课程设计”   9. 点击编辑-查找下一个 |

 

 

| 用例名称   | 字体                                       |
| ------ | ---------------------------------------- |
| 涉及的参与者 | 用户                                       |
| 用例描述   | 在Windows 环境下，新建一个空白txt文档                 |
| 前置条件   | 记事本系统可用                                  |
| 正常事件流  | 1. 在记事本系统界面，点击格式-字体  2.  在编辑区域输入“软件工程课程设计”，字体改为Wingdings，点击确定   3. 选择字体-斜体  4.  选择字体-8 |

 

### 3.3系统功能实现

#### 3.3.1时序图

![未命名文件 (1)](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image006.png)

#### 3.3.2类图(只选取部分函数)

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image008.jpg)

### 3.4系统角色

用户可以在系统里创建新文件，编辑文字，并保存，以便查看，还可以进行批处理文件等操作。

### 3.5系统流程图

#### 3.5.1主流程图

如下图所示，打开记事本后，可在文本域进行文本输入；或者进行一系列执行操作包括：文件、编辑、格式以及帮助菜单。

l 功能描述：打开文件、编辑、格式以及帮助菜单

l 输入项：点相关按钮

l 输出项：做出指定动作

l 流程图：

![未命名文件 (2)](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image010.png)

#### 3.5.2文件菜单操作流程图

 文件菜单操作流程如下图，当打开文件菜单时，下拉显示子菜单包括新建、打开、保存、退出等功能。

 

l功能描述：实现文件新建、打开、保存、另存为、退出功能

l输入项：点相关按钮

l输出项：做出指定动作

l流程图：

![未命名文件 (1)](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image012.png)

#### 3.5.3 编辑菜单操作流程图

编辑菜单操作流程如下图，当打开编辑菜单时，下拉显示子菜单包括复制、粘贴、剪切、全选、查找、替换等功能。

l  功能描述：实现文本的剪切、复制、粘贴、撤销、查找、替换、删除功能

l  输入项：点相关按钮

l  输出项：做出指定动作

l  流程图：

![未命名文件 (4)](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image014.png)

#### 3.5.4格式菜单操作流程图

格式菜单操作流程如下图，当打开格式菜单时，下拉显示子菜单包括自动换行、格式、字体颜色等功能。

l  功能描述：设置自动换行、字体格式、字体颜色、背景颜色

l  输入项：点格式按钮

l  输出项：设置成自动换行，以及自己想要的字体格式、字体颜色、背景颜色

l  流程图：

![未命名文件 (5)](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image016.png)

#### 3.5.5帮助菜单操作流程图

帮助菜单操作流程如下图，当打开帮助菜单时，下拉显示子菜单关于记事本。

l  功能描述：查看帮助信息

l  输入项：点帮助按钮

l  输出项：显示相关信息

l  流程图：

![未命名文件 (6)](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image018.png)

### 3.6数据流图

**![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image020.jpg)**

### 3.7数据字典

由于无数据库设计，所以无数据字典描述。

 

## 四、概要设计

### 4.1系统运行环境

#### 4.1.1操作系统

操作系统无关性，Windows XP/7/8.1/10、Linux、Mac OS X下安装了Java的运行环境JRE即可运行。

JDK版本：1.8

#### 4.1.2使用软件：

代码编写：Eclipse

数据库：无

建模工具：Rational Rose（自写）

文档编写：Microsoft Word 2016

#### 4.1.3开发语言

Java

### 4.2系统总体设计

#### 4.2.1基本设计概念和处理流程

##### 4.2.1.1 全局E-R图

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image022.jpg)

##### 4.2.1.2 分E-R图

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image024.png)![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image026.png)![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image028.png)

#### 4.2.2系统总体结构与模块

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image030.png)

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image032.png)

### 4.3接口设计

#### 4.3.1.外部接口

##### 1) 用户界面

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image034.png)

##### 2) 软件接口

软件运行平台：Eclipse

##### 3) 硬件接口

硬件运行平台：PC端

#### 4.3.2.内部接口

说明各个模块由谁调用，完成什么功能，完成后转入什么状态

| 模块                     | 由谁调用             | 功能          | 完成后转入的状态 |
| ---------------------- | ---------------- | ----------- | -------- |
| clock                  | NotepadMainFrame | 显示状态栏的时间    | 无        |
| MQFontChooser          | NotepadMainFrame | 字体选择器       | 字体变更     |
| textLine               | NotepadMainFrame | 左边的行号       | 无        |
| 状态栏                    | NotepadMainFrame | 状态栏显示信息     | 显示状态栏    |
| MainFrameWidowListener | NotepadMainFrame | 退出窗口选择设置    | 退出软件     |
| actionPerformed        | NotepadMainFrame | 记事本的状态操作    | 更换操作模式   |
| exit，mySearch，paste等   | NotepadMainFrame | 退出，查找，暂停等操作 | 记事本状态改变  |

### 4.4 数据结构设计

由于没有用到数据库设计，所以无数据结构设计。

## 五、详细设计

### 5.1.    数据流

源点/终点：用户

处理：编辑（包括撤销、复制、剪贴、粘贴等）、新建记事本、保存、打开记事本、格式、打印

数据流：输入的字符，记事本，打印文档

数据存储：本地磁盘

 

|      |                                          |
| ---- | ---------------------------------------- |
|      | ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image035.png) |

此记事本的基本系统模型如下图

细化后的数据流图如下图

 

|      |                                          |
| ---- | ---------------------------------------- |
|      | ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image036.png) |

### 5.2.    层次方框图

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image038.png)

 

### 5.3.    功能模块图

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image040.png)

## 六、系统实现

### 1)关键代码

#### 1、自动换行

JTextArea有自己定义的策略。

textArea.setLineWrap(true);//设置文本区的换行策略。如果设置为 true，则当行的长度大于所分配的宽度时，将换行。此属性默认为 false。

#### 2、背景颜色

JColorChooser jcc1 = **new** JColorChooser();

JOptionPane.*showMessageDialog*(**this**, jcc1,"选择背景颜色颜色",-1);

 color = jcc1.getColor();

 textArea.setBackground(color);

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image042.jpg)

#### 3、字体颜色

jcc1=**new** JColorChooser();

​            JOptionPane.*showMessageDialog*(**this**, jcc1, "选择字体颜色", -1);

​            color = jcc1.getColor();

​            //String string=textArea.getSelectedText();

​            textArea.setForeground(color);

#### 4、鼠标右击菜单

// 创建弹出菜单

​        **final** JPopupMenu jp=**new** JPopupMenu();    //创建弹出式菜单，下面三项是菜单项

​        textArea.addMouseListener(**new** MouseAdapter() {

​            @Override

​            **public** **void** mouseClicked(MouseEvent e) {

​                **if**(e.getButton()==MouseEvent.**BUTTON3**)//只响应鼠标右键单击事件

​                {

​                    jp.show(e.getComponent(),e.getX(),e.getY());//在鼠标位置显示弹出式菜单

​                }

​            }

   });

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image044.jpg)

#### 5、打印功能

 **public** **void** Print()

​    {

​        **try**{

​            p = getToolkit().getPrintJob(**this**,"ok",**null**);//创建一个Printfjob 对象 p

​            g = p.getGraphics();//p 获取一个用于打印的 Graphics 的对象

​            //g.translate(120,200);//改变组建的位置 

​            **this**.textArea.printAll(g);

​            p.end();//释放对象 g  

​        }

​        **catch**(Exception a){

 

​        } 

  }
![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image046.jpg)

#### 9、显示时间

//用到了线程，每1秒刷新一次时间
**public** **class** Clock **extends** Thread{  

  

​    **public** **void** run() {  

​        **while** (**true**) {  

​            GregorianCalendar time = **new** GregorianCalendar();  

​            **int** hour = time.get(Calendar.**HOUR_OF_DAY**);  

​            **int** min = time.get(Calendar.**MINUTE**);  

​            **int** second = time.get(Calendar.**SECOND**);  

​            NotepadMainFrame.*label1*.setText("   当前时间：" + hour + ":" + min + ":" + second);  

​            **try** {  

​                Thread.*sleep*(1000);  

​            } **catch** (InterruptedException exception) {  

​            } 

​        } 

​    }  

}

在NotepadMainFrame类中
**JToolBar** toolState = **new** JToolBar();
toolState.setSize(textArea.getSize().width, 10);//toolState.setLayout(new
FlowLayout(FlowLayout.**LEFT**));
toolState = **new** JToolBar();

​        toolState.setSize(textArea.getSize().width,10);//toolState.setLayout(newFlowLayout(FlowLayout.LEFT));

​        *label1* = **new** JLabel("   当前系统时间：" + hour + ":" + min + ":" + second+" ");

​        toolState.add(*label1*);
Clock
clock=new Clock();
clock.start();

#### 10、显示行数和列数

label2 = **new** JLabel("   第 " + linenum + " 行, 第 " + columnnum+" 列 ");

​        toolState.add(label2);

​        toolState.addSeparator();

textArea.addCaretListener(**new **CaretListener() {  
​     //记录行数和列数
​    **public
void**
caretUpdate(CaretEvent e) {
​    JTextArea editArea = (JTextArea)e.getSource();
​       ** try** {
​           ** int** **caretpos** = editArea.getCaretPosition();
​            linenum =
editArea.getLineOfOffset(caretpos);
​            columnnum =
caretpos - textArea.getLineStartOffset(linenum);
​            linenum +=
1;
label2.setText("    第 " + linenum + " 行, 第 " + (columnnum+1)+" 列  ");
​        }
​    **catch**(Exception ex) { }
}});
contentPane.add(toolState, BorderLayout.SOUTH);
toolState.setVisible(**false**);
toolState.setFloatable(**false**);

 

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image048.jpg)

#### 11、撤销、返回

初始化一个UndoManger，然后通过body.getDocument().addUndoableEditListener(undoMgr)这个方法，就可以把撤销管理器的监听器添加到TextArea中。需要调用撤销的时候就调用unoMgr.undo()方法。

UndoManager undoMgr=**new **UndoManager();
JtextArea textArea.getDocument().addUndoableEditListener(undoMgr);
   if(undoMgr.canUndo()){
​     undoMgr.undo();//撤销
}
   if(undoMgr.canRedo()){
​     undoMgr.redo();//恢复
}

### 2)程序截图

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image049.png)

## 七、系统测试

### 7.1 测试方法简述

运行项目，进行整体测试。

设计测试用例的方法一般有两种：黑盒测试法和白盒测试法。 

(1) 黑盒测试。如果已经知道产品应该具有的功能，可以通过测试来检验每个功能

是否够正常使用，这样的测试称为黑盒测试，也叫做功能测试。黑盒测试法是将其看

作一个黑盒子，完全不用考虑程序内部结构和处理过程。也就是说，黑盒是对程序接

口进行的测试，它只检查程序功能是否能按照预期目标正常使用，程序是否能正确的

接收输入的数据、处理数据、输出数据，并保证外部信息(如数据库)的完整性。 

(2) 白盒测试。如果知道了产品内部工作过程，可以通过测试来检验产品内部动作

是否按照预期的规定正常进行，这样的方法称为白盒测试，也叫做结构测试。与黑盒

相反，白盒测试法的前提是把程序看做装在一个透明的盒子里，按照程序内部的逻辑

测试程序，检验程序中的每条是否都按预定的要求正确工作。 

本系统采用的测试用例方法是黑盒测试法，将系统所有可能的值来检查程序的正

确性。

需要测试的功能项是：

（1）“文件”主菜单中的“新建”、“打开”、“保存”、“另存为”、“页面设置”、“打印”、“退出”这几个子功能。

（2）“编辑”主菜单中的“撤销”、“剪切”、“复制”、“粘贴”、“删除”、“查找”、“查找下一个”、“替换”、“转到”、“全选”、“日期/时间”这几个子功能。

（3）“格式”主菜单中的“自动换行”、“字体”、“背景颜色”、“字体颜色”这四个子功能。

（4）“查看”主菜单中的“状态栏”子功能。

（5）“帮助”主菜单中的“查看帮助”、“关于记事本”这两个子功能。

### 7.2 测试用例

#### 7.2.1新建

| **软件名称******                             | 记事本                      | **模块名称******                             | 新建         |      |      |
| ---------------------------------------- | ------------------------ | ---------------------------------------- | ---------- | ---- | ---- |
| **设计者******                              | 杨宇杰                      | **创建日期******                             | 2017-06-21 |      |      |
| **设计状态******                             | 初稿                       | **用例类型******                             | 手工操作       |      |      |
| **用例描述******  **        **在windows环境下，测试新建一个空白txt文档 |                          |                                          |            |      |      |
| **目的******                               | 验证能实现新建空白txt文档的功能        |                                          |            |      |      |
| **前提条件******                             | 记事本系统可用                  |                                          |            |      |      |
| **测试步骤及输入：******                         | **结果：******              |                                          |            |      |      |
| 步骤1                                      | 点击开始-所有程序-附件-记事本         | 成功进入记事本系统                                |            |      |      |
| 步骤2                                      | 在记事本系统界面，点击文件-新建(ctrl+N) | 新建一个空白文档                                 |            |      |      |
| 步骤3                                      | 在编辑区输入13132123           | 显示输入值：13132123                           |            |      |      |
| 步骤4                                      | 在编辑区输入杨宇杰                | 显示输入值：杨宇杰                                |            |      |      |
| 步骤5                                      | 在编辑区输入yangyujie          | 显示输入值：yangyujie                          |            |      |      |
| 步骤6                                      | 在编辑区输入@#￥%……￥%           | 显示输入值：@#￥%……￥%                           |            |      |      |
| 步骤7                                      | 点击文件-新建(ctrl+N)          | 系统提示  ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image051.jpg)：  点击是保存，点击否不保存，点击取消撤销新建功能 |            |      |      |
| 步骤8                                      | 在桌面点击右键，选择新建-文本文档        | 桌面新建一个![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image053.jpg)，双击打开为空白文档 |            |      |      |
|                                          |                          |                                          |            |      |      |

#### 7.2.2打开

| **软件名称******                             | 记事本                  | **模块名称****** | 新建         |      |      |
| ---------------------------------------- | -------------------- | ------------ | ---------- | ---- | ---- |
| **设计者******                              | 杨宇杰                  | **创建日期****** | 2017-06-21 |      |      |
| **设计状态******                             | 初稿                   | **用例类型****** | 手工操作       |      |      |
| **用例描述******  **        **在windows环境下，测试打开一个空白txt文档 |                      |              |            |      |      |
| **目的******                               | 验证能实现打开txt文档的功能      |              |            |      |      |
| **前提条件******                             | 记事本系统可用              |              |            |      |      |
| **测试步骤及输入：******                         | **结果：******          |              |            |      |      |
| 步骤1                                      | 双击打开记事本              | 成功进入记事本系统    |            |      |      |
| 步骤2                                      | 左键单击记事本-点击打开(ctrl+O) | 成功进入记事本系统    |            |      |      |
|                                          |                      |              |            |      |      |

#### 7.2.3保存或另存为

| **软件名称******                             | 记事本                            | **模块名称******        | 新建         |      |      |
| ---------------------------------------- | ------------------------------ | ------------------- | ---------- | ---- | ---- |
| **设计者******                              | 杨宇杰                            | **创建日期******        | 2017-06-21 |      |      |
| **设计状态******                             | 初稿                             | **用例类型******        | 手工操作       |      |      |
| **用例描述******  **        **在windows环境下，测试保存一个空白txt文档 |                                |                     |            |      |      |
| **目的******                               | 验证能实现保存txt文档的功能                |                     |            |      |      |
| **前提条件******                             | 记事本系统可用                        |                     |            |      |      |
| **测试步骤及输入：******                         | **结果：******                    |                     |            |      |      |
| 步骤1                                      | 打开空白记事本，点击文件-保存(ctrl+S)-再次打开   | 成功进入记事本系统           |            |      |      |
| 步骤2                                      | 在编辑区域输入杨宇杰，点击文件-保存-再次打开        | 文本显示输入值：杨宇杰         |            |      |      |
| 步骤3                                      | 在编辑区域输入：、杨宇杰，Ctrl+S，双击记事本      | 文本显示输入值：杨宇杰、杨宇杰     |            |      |      |
| 步骤4                                      | 在编辑区域输入：、杨宇杰，点击文件-另存为-保存-再次打开  | 文本显示输入值：杨宇杰、杨宇杰、杨宇杰 |            |      |      |
| 步骤5                                      | 在编辑区域输入：、杨宇杰，点击文件-另存为-不保存-再次打开 | 文本显示输入值：杨宇杰、杨宇杰     |            |      |      |
|                                          |                                |                     |            |      |      |

#### 7.2.4页面设置和打印

| **软件名称******                             | 记事本                | **模块名称******                             | 新建         |      |      |
| ---------------------------------------- | ------------------ | ---------------------------------------- | ---------- | ---- | ---- |
| **设计者******                              | 杨宇杰                | **创建日期******                             | 2017-06-21 |      |      |
| **设计状态******                             | 初稿                 | **用例类型******                             | 手工操作       |      |      |
| **用例描述******  **        **在windows环境下，测试一个空白txt文档的页面设置和打印功能 |                    |                                          |            |      |      |
| **目的******                               | 验证能对txt文档进行页面设置和打印 |                                          |            |      |      |
| **前提条件******                             | 记事本系统可用            |                                          |            |      |      |
| **测试步骤及输入：******                         | **结果：******        |                                          |            |      |      |
| 步骤1                                      | 打开文件-页面设置          | 系统显示  ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image055.jpg) |            |      |      |
| 步骤2                                      | 打开文件-打印(Ctrl+P)    | 系统显示  ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image057.jpg) |            |      |      |
|                                          |                    |                                          |            |      |      |

#### 7.2.5编辑

| **软件名称******                             | 记事本                             | **模块名称******                             | 新建         |      |      |
| ---------------------------------------- | ------------------------------- | ---------------------------------------- | ---------- | ---- | ---- |
| **设计者******                              | 杨宇杰                             | **创建日期******                             | 2017-06-21 |      |      |
| **设计状态******                             | 初稿                              | **用例类型******                             | 手工操作       |      |      |
| **用例描述******  **        **在windows环境下，测试编辑一个空白txt文档 |                                 |                                          |            |      |      |
| **目的******                               | 验证能实现打开txt文档的功能                 |                                          |            |      |      |
| **前提条件******                             | 记事本系统可用                         |                                          |            |      |      |
| **测试步骤及输入：******                         | **结果：******                     |                                          |            |      |      |
| 步骤1                                      | 在编辑区输入123123                    | 显示输入值：123123                             |            |      |      |
| 步骤2                                      | 在编辑区输入杨宇杰                       | 显示输入值：杨宇杰                                |            |      |      |
| 步骤3                                      | 在编辑区输入yangyujie                 | 显示输入值：yangyujie                          |            |      |      |
| 步骤4                                      | 在编辑区输入#$%$%                     | 显示输入值：#$%$%                              |            |      |      |
| 步骤5                                      | 点击编辑-撤销(Ctrl+Z)                 | 显示内容：#$%$                                |            |      |      |
| 步骤6                                      | 点击编辑-剪切(Ctrl+X)，选择的内容是yangyujie | 选中内容消失                                   |            |      |      |
| 步骤7                                      | 点击编辑-复制(Ctrl+C)，选择的内容是yangyujie | 选中内容没变化                                  |            |      |      |
| 步骤8                                      | 点击编辑-粘贴(Ctrl+V)，光标在yangyujie后面  | 显示内容：yangyujieyangyujie                  |            |      |      |
| 步骤9                                      | 点击编辑-删除(Del)，选择的内容是yangyujie    | 显示内容是：yangyujie                          |            |      |      |
| 步骤10                                     | 点击编辑-查找(Ctrl+F)，查找的内容是r         | 显示内容：r字符蓝色标记  ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image059.jpg) |            |      |      |
| 步骤11                                     | 点击编辑-查找下一个(F3)，查找的内容是r          | 显示内容，选择一次，则r相应的后一个字符转变为蓝色，没有则显示  ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image061.jpg) |            |      |      |
| 步骤12                                     | 点击编辑-替换(Ctrl+H),第一个r替换为w        | 显示内容：r成功替换为w                             |            |      |      |
| 步骤13                                     | 点击编辑-全选(Ctrl+A)                 | 显示内容：字体颜色全部变为蓝色  ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image063.jpg) |            |      |      |
| 步骤14                                     | 点击编辑-时间/日期(F5)                  | 显示内容：  ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image065.jpg) |            |      |      |
|                                          |                                 |                                          |            |      |      |

 

#### 7.2.6自动换行

| **软件名称******                             | 记事本                            | **模块名称****** | 新建         |      |      |
| ---------------------------------------- | ------------------------------ | ------------ | ---------- | ---- | ---- |
| **设计者******                              | 杨宇杰                            | **创建日期****** | 2017-06-21 |      |      |
| **设计状态******                             | 初稿                             | **用例类型****** | 手工操作       |      |      |
| **用例描述******  **        **在windows环境下，测试记事本的自动换行功能 |                                |              |            |      |      |
| **目的******                               | 验证能实现记事本的“自动换行”和 “非自动换行”状态转换功能 |              |            |      |      |
| **前提条件******                             | 记事本系统可用                        |              |            |      |      |
| **测试步骤及输入：******                         | **结果：******                    |              |            |      |      |
| 步骤1                                      | 双击打开记事本，选择格式下的自动换行             | 换行成功         |            |      |      |
| 步骤2                                      | 在空白区域里输入的汉字超过一行字的范围，点击自动换行     | 换行成功         |            |      |      |
| 步骤3                                      | 关闭自动换行功能，在空白区域写超过一行字的范围的内容     | 不能够自动换行      |            |      |      |
|                                          |                                |              |            |      |      |

 

#### 7.2.7字体大小颜色以及背景颜色

 

| **软件名称******                             | 记事本                               | **模块名称******                             | 新建         |      |      |
| ---------------------------------------- | --------------------------------- | ---------------------------------------- | ---------- | ---- | ---- |
| **设计者******                              | 杨宇杰                               | **创建日期******                             | 2017-06-21 |      |      |
| **设计状态******                             | 初稿                                | **用例类型******                             | 手工操作       |      |      |
| **用例描述******  **        **在windows环境下，测试记事本的更换字体样式以及更换背景颜色的功能 |                                   |                                          |            |      |      |
| **目的******                               | 验证能实现记事本的更换字体样式以及更换背景颜色的功能        |                                          |            |      |      |
| 前提条件                                     | 记事本系统可用                           |                                          |            |      |      |
| 测试步骤及输入：                                 | 结果：                               |                                          |            |      |      |
| 步骤1                                      | 双击打开记事本，点击格式-字体                   | 选择相应的字体，有相应的改变                           |            |      |      |
| 步骤2                                      | 在编辑区域输入1310906，字体改为Wingdings，点击确定 | 显示：字体改为Wingdings样式                       |            |      |      |
| 步骤3                                      | 在编辑区输入杨宇杰，字体改为Giddyup Std，点击确定    | 显示  ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image067.jpg) |            |      |      |
| 步骤4                                      | 选择粗体 斜体                           | 能够成功改变所选字的字形                             |            |      |      |
| 步骤5                                      | 选择粗体                              | 能够成功改变所选字的字形                             |            |      |      |
| 步骤6                                      | 选择常规                              | 能够成功改变所选字的字形                             |            |      |      |
| 步骤7                                      | 选择斜体                              | 能够成功改变所选字的字形                             |            |      |      |
| 步骤8                                      | 在编辑区输入1310906                     | 成功改变字体：  （改变前）  ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image069.jpg)  （改变后）  ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image071.jpg) |            |      |      |
| 步骤9                                      | 在编辑区输入杨宇杰                         | 成功改变字体  （改变前）  ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image073.jpg)  （改变后）  ![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image075.jpg) |            |      |      |
| 步骤10                                     | 选择五号字体                            | 点击确定，能够成功改变字体大小                          |            |      |      |
| 步骤11                                     | 选择四号字体                            | 点击确定，能够成功改变字体大小                          |            |      |      |
| 步骤12                                     | 将背景颜色设置为深灰色                       | 点击确定，能够成功改变背景颜色                          |            |      |      |
| 步骤13                                     | 将字体颜色设置为白色                        | 点击确定，能够成功改变字体颜色                          |            |      |      |
|                                          |                                   |                                          |            |      |      |

最终界面如下：

![img](file:///C:/Users/Simple_Y/AppData/Local/Temp/msohtmlclip1/01/clip_image077.jpg)

### 7.3 测试评价

针对实现的记事本的功能模块，基本上达到了预定的要求。

缺陷（未实现功能）：

1）右键的菜单响应功能中的从右到左，Unicode码，汉字重选。
2）保存的文件设置了颜色和字体，打开后还是默认大小。
3）打印功能还可以再完善，现在只能打印一页多点，具体的设置还不是很懂，等我再多学点。
4）将自动换行和状态显示默认添加。

 

## 八、总结

### 8.1.    组长总结   

#### 8.1.1.负责的工作 

我在本次课程设计中主要负责编码和文档排版。在开始阶段，我思考并分析问题，建立了对象模型，动态模型，功能模型等，将记事本分解成若干个模块，每个模块实现一个独立的功能，然后分别去实现每一个模块，实现了在系统记事本原有功能上做一些改进。对编写文档进行分工：



#### 8.1.2. 遇到的问题     

1、发现一个小问题，我打开保存过的文件，修改了一部分，然后按ctrl+s没有用，无论我退出还是新建、打开，都会提示我再保存。但是我在菜单上选择保存，就是正常的使用，这真有点奇怪。
​    2、还有一个问题，我在NotepadMainFrame类中，获取不到正确的保存路径，一直为Null，也就是我设置的默认值。后来封装到方法中就没有问题了，下次做项目的时候注意点。

3、过程中发现自己对io流不熟悉，对API的使用更是一知半解。

#### 8.1.3. 个人收获   

在撰写各部分文档的过程中，不断深入了解软件工程这一门学科。也深切体会到，一个软件的开发需要一步步脚踏实地地进行。从一开始就要进行可行性的分析，排除无用的软件开发项目；需求分析能让我们从各方面了解清楚这个软件的作用，需要达到的目标；概要设计描述了整个项目的整体框架，以及结构设计；详细设计则从每一个模块仔细描述模块功能及实现流程，为后续的编码开发指明方向。一份好的开发文档是一个软件成功开发成功的前提基础，也会避免软件开发走上歪路，减少不必要的时间、金钱损失。

五个人合作撰写这一份文档也花费了许多时间，遇到了许多困难以及迷惑，也足以证明，一份好的开发文档也是需要一定技术基础以及经验积累才能写得出来。但是在这一个过程中，我们收获到了许多有用的知识，必定对我们以后的职业道路有所帮助。