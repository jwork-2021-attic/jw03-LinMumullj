## 1. 写下对代码工作原理的理解；

老师的代码通过`SteganographyFactory`生成隐写术图。也就是将图片RGB或比特进行一些修改来存储数据。通过传入java文件的名字到对应的目录下找到java文件并进行编译，得到class文件；`SteganographyEncode`中，将编译生成的class文件的内容混入读取到的图片内容中，最后再把混合后的内容生成png图片。`SteganographyClassLoader`重写了findClass方法，传入一个图片的url保存在loader对象中。

## 2. 将自己在`W02`中实现的两个排序算法（冒泡排序除外）分别编码进自选图片得到隐写术图，在markdown中给出两个图片的URL；

Quicksort:

https://github.com/jwork-2021/jw03-LinMumullj/blob/main/example.myQuickSorter.png

Shellsort:

https://github.com/jwork-2021/jw03-LinMumullj/blob/main/example.ShellSorter.png

## 3. 用你的图片给`W02`中example的老头赋予排序能力，得到排序结果（动画），上传动画到asciinema，在markdown中给出两个动画的链接。

Quicksort:

https://www.bilibili.com/video/BV1RL411s7CS?share_source=copy_web

Shellsort:

https://www.bilibili.com/video/BV1cL4y167sM?share_source=copy_web

## 4. 联系另一位同学，用他的图片给`W02`中example的老头赋予排序能力，在markdown中记录你用的谁的图片，得到结果是否正确。

我用了张峻同学的南大标志图片。文件中的QuickSorter.png。结果也正确。