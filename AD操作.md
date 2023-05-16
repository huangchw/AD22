# AD22

## 一、禁用网络功能

![image-20230515160735440](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515160735440.png)

## 二、添加库文件

1、添加全局库：选择第一项



![image-20230515160814068](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515160814068.png)

2、添加工程专用库：直接在工程中选择添加已有文件到工程

![image-20230515161037703](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515161037703.png)

## 三、库的使用

切换当前库

![image-20230515161326709](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515161326709.png)



## 四、库绘制

### 1、原理图库绘制

直接根据题目给出的样式、大小、线型绘制即可，注意单位切换。

### 2、PCB封装库绘制

若给的是器件的规格，则需要设计焊盘大小，对于直插器件，要保证能够插进去，焊盘具有一定的环宽。

若给出的焊盘设计要求的尺寸，按照尺寸绘制即可。若对焊盘有引脚顺序要求，则注意焊盘的顺序命名

## 五、动态标题栏

1、放置文本

2、选择文本，打开文本属性properties

3、在文本中，通过下拉框选择需要的变量名

![image-20230515164634919](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515164634919.png)

4、若有新的变量名，则需在页面的properties中，先添加变量名，再返回第三步操作

![image-20230515165115432](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515165115432.png)



实现效果：

![image-20230515170955746](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515170955746.png)

## 六、原理图模板的使用

1、将设计号的模板，放在模板对应的路径下（注意复制的方式，答题目录里面要按照求进行保留）

![image-20230515172043687](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515172043687.png)

2、设置模板，根据需要调整模式

![image-20230515172842282](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515172842282.png)

## 七、层次电路图设计

https://blog.csdn.net/qq_38351824/article/details/100970715

### 1、在母图上放置页面符

![image-20230515203432501](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515203432501.png)



### 2、给sheet symbol添加Entry,名字与子图原理图中的网络名一致，并设置端口属性

![image-20230515203537612](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515203537612.png)

![image-20230515203836781](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515203836781.png)

### 3、生成子图

![image-20230515203703005](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515203703005.png)

### 4、保存生成的子图，在子图中绘制对应的原理图

![image-20230515203913049](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515203913049.png)



### 七、叠层设置

### 1、进入菜单

![image-20230515204814427](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515204814427.png)

### 2、选择芯材

![image-20230515204313813](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515204313813.png)

### 3、添加plan层

![image-20230515204520676](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515204520676.png)

### 4、按题目要求修改叠层名称

![image-20230515204703841](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515204703841.png)

### 5、保存，退出

## 八、电源层分割

### 1、选中电源层

![image-20230515205839951](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515205839951.png)



### 2、使用画line分割，快捷键P+L

![image-20230515205930614](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515205930614.png)

### 3、设置线宽，并画线分割不同电源（地）区域，一般要比走线要宽一点

![image-20230515210049045](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515210049045.png)



### 4、双击某一闭合区域，设置铜皮网络

![image-20230515210134822](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515210134822.png)

## 九、全局网络设置

在工程中，除非有特殊要求，一般将网络设置成全局网络，即整个工程中同名的网络全部连接在一起

![image-20230515161750622](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230515161750622.png)



## 十、QFN封装扇出

### 1、布线规则设置

在进行自动扇出前，需要满足一下要求

（1） 选择合适的线宽及过孔大小，即设置好线宽、间距、过孔大小等规则。

（2） BGA内部没有任何元素对象，如布线或者过孔等。
![image-20230516084244034](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516084244034.png)

### 2、扇出规则设置

fanout_BGA(球栅阵列封装扇出布线)

fanout_LCC(无引脚芯片封装扇出布线)

fanout_SOIC(小外形封装)

fanout_small(元器件引脚少于五个的小型封装)

fanout_default(系统默认扇出布线)

![image-20230516082432144](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516082432144.png)

### 3、属性设置

![image-20230516082725151](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516082725151.png)

Fanout style：扇出类型，用于选择扇出过孔与SMT元器件的放置关系。有auto(扇出过孔自动放置在最佳位置)，inline rows(扇出过孔放置成两个直线的行)，staggered rows(扇出过孔放置成两个交叉的行)，BGA(扇出重现BGA)，under pads(扇出过孔直接放置在SMT元器件的焊盘下)这5中选择。

![image-20230516082803326](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516082803326.png)

Fanout direction：扇出方向，用于确定扇出的方向。有disable(不扇出)，in only(向内扇出)，out only(想歪扇出)，in then out(先向内扇出，空间不足时再向外扇出)，out then in(先向外扇出，空间不足时再向内扇出)，alternating in and out(扇出时先内后外交替进行)这6种选择。

![image-20230516082819617](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516082819617.png)

Direction from pad：焊盘扇出方向选择项。有away from center(以45°向四周扇出)，north-east(以向北向45°扇出)，south-east(以东南向45°扇出)，north-west(以西南向45°扇出)，north-west(以西北向45°扇出)，toward center(向中心扇出)这6种选择。

![image-20230516082840954](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516082840954.png)

Via placement mode：扇出过孔放置模式。有close to pad(follow rules)---接近焊盘和centered between pads---两焊盘之间这2个选择。---在自动布线时需要设置

### 4、布局布线规则设置

要保证能够正常将线引出，这个规则应该是布线前就按照题目要求设置好的。



### 5、选择器件，进行扇出

![image-20230516084523012](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516084523012.png)

### 6、扇出对话框选择

（1） 无网络焊盘扇出：勾选此选项，无网络的焊盘会删出；不勾选则不会扇出。

（2） 扇出外面2行焊盘：勾选时，最外面2行焊盘会扇出；不勾选，则不会扇出。

（3） 扇出完成后包含逃逸布线：勾选时，扇出并从焊盘引线出来。

（4） 有盲埋孔扇出。

==QFN扇出时，可全部不勾选。==

![image-20230516084639682](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516084639682.png)

### 7、扇出效果

![image-20230516085100415](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516085100415.png)

## 十一、网表的导出方法

### 1、生成网表

在Design中选择输出工程网表，然后选择题目要求的网表类型即可。如果有错误，根据错误提示处理完错误。

![image-20230516085746601](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516085746601.png)

### 2、保存网表文件

生成的腕表文件在工程目录树里面。如果题目要求了保存的名称了位置，则另存一下即可。

![image-20230516090226111](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516090226111.png)

## 十二、生产文件的输出

### 1、装配图输出

#### 1） 文件---pdf输出

![image-20230516090415733](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516090415733.png)



#### 2） 选择当前文件

![image-20230516090525236](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516090525236.png)

#### 3）不生成材料表

![image-20230516090608857](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516090608857.png)

#### 4）右键---创建装配图

![image-20230516090653360](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516090653360.png)

#### 5）双击TOP层，设置TOP后同样的步骤设置bottom层

![image-20230516090816202](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516090816202.png)

#### 6）删除除丝印层外的其他层，并增加板框层和顶层阻焊层（根据自己设置的层叠，板框层一般放在keepout层或者机械1层）

![image-20230516091059318](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516091059318.png)

#### 7）同样的方法处理bottom层

![image-20230516091152974](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516091152974.png)

#### 8）勾选过孔和底面镜像

![image-20230516091245964](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516091245964.png)

#### 9）设置颜色，默认的灰度即可

![image-20230516091345071](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516091345071.png)

#### 10）输出。根据题目要求修改名字放置在要求的文件夹下即可。

![image-20230516091527314](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516091527314.png)

### 2、BOM表输出

#### 1）选择输出bom

![image-20230516091645095](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516091645095.png)

#### 2）保留需要的列

![image-20230516091958572](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516091958572.png)

#### 3）删除不需要的列

选择列，然后在下面把不需要的列前面的小眼睛删掉

![image-20230516092031952](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516092031952.png)

#### 4）选择输出，并按要求保存

![image-20230516101515483](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516101515483.png)

### 3、Gerber（光绘文件）文件输出

gerber文件是将PCB图中的布线数据转化为能被光绘机处理的文件，被光绘机用于生产1:1高精度的胶片。

#### 1)进入gerber输出界面：File->Fabrication Outputs->Gerber Files

![image-20230516101620814](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516101620814.png)

#### 2）General设置

我们一般设置Inches英寸，Format格式一般设置2:4，2:3，2:4，2:5 代表的是精度，设置的精度越高，对PCB制造设备的要求也就越高，具体精度下方文字都有说明。

![image-20230516101819259](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516101819259.png)

#### 3）输出层设置，设置为used on，注意不要镜像层。

![image-20230516101913517](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516101913517.png)

#### 4）红框里面仅保留板框层，如果放在机械1层则只勾选机械1，如果放在keepout层则只勾选keepout层

![image-20230516102201330](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516102201330.png)

#### 5）Drill Drawing（钻孔图层）设置

![image-20230516102324333](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516102324333.png)

#### 6）光圈：默认设置即可

![image-20230516102342519](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516102342519.png)

#### 7）advanced默认即可，如果生成的gerber文件不全，则将XY size每个增加一个0

![image-20230516102415960](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516102415960.png)

#### 8）点击OK，生成gerber文件，并保存

![image-20230516102513492](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516102513492.png)

#### 9）在工程树里面可以找到生成的每个图层的gerber文件，在windows下将对应的文件拷贝到题目要求的位置即可

![image-20230516103615651](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516103615651.png)

### 4、钻孔文件输出

#### 1）在PCB文件中进入菜单：File->Fabrication Outputs->NC Drill Files

![image-20230516102822416](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516102822416.png)

#### 2）设置单位和格式

![image-20230516102900412](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516102900412.png)

#### 3）默认，点击确定生成钻孔文件

![image-20230516102941957](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516102941957.png)

#### 4）按要求保存文件

![image-20230516103004624](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516103004624.png)

### 3、输出坐标文件

输出坐标文件是给SMT厂家定位器件用的

#### 1）File->assembly Outputs->Generates pick and place files

![image-20230516103116079](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516103116079.png)

#### 2）去掉Description（没用），选择英制，选择文本格式（如果题目要求csv就生成csv），点击OK生成

![image-20230516103219445](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516103219445.png)

#### 3）在工程里面找到生成的txt文档

![image-20230516103323828](https://aliyun-picture-picgo.oss-cn-shenzhen.aliyuncs.com/image-20230516103323828.png)