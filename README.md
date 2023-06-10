## 一个自用的YumikoToys-MTMR规则

因为很喜欢Touch Bar故购入了MacBook Pro M1

🐱当我在看涩涩电影的时候（x）
🐷当我在看各种全屏类的视频/游戏的时候苦于需要鼠标才能调节亮度和音量

所以在找到MTMR 「https://github.com/Toxblh/MTMR」 🐭这个神器之后终于定制了自己的规则

然后 再也不想碰这么奇怪的Touch Bar了（bushi)

## 文件说明

```
├── .MTMR Rules-2.60
    ├── .mtmr - 规则需要用到的图标和脚
    ├── items.json - MTMR规则文件
```

写的很垃圾 部分没实现 反正能跑就不是事

## 程序BUG和缺陷
- 程序最小化会有2个托盘图标（用于添加电源方案）
- 部分情况下会失效（会让合盖不睡眠功能失效）
- 没做获取电池最大容量的代码

## 截图
![Snipaste_2023-01-18_15-27-44](https://user-images.githubusercontent.com/8959123/213109841-c4a7b310-6801-44af-b2a6-8223650e077b.png)
![Snipaste_2023-01-18_15-29-07](https://user-images.githubusercontent.com/8959123/213110072-69c2b547-9e3f-4f04-ac7e-797d5bf91b55.png)


## 程序准备工作

- clone 仓库的代码
- 打开VS Studio
- 修改界上的元素面
- 保存并生成

编译后去bin文件夹下找exe食用即可

### 额外说明

##### 编译环境

Visual Studio 2022 Preview

Windows 11 Home Insider Preview 10.0.25276 Build 25276（破苏菲自带的系统）


## 想说的

本程序写的很烂 市面上能实现类似功能的成熟的工具很多 该项目纯属想自定义一个自己的工具罢了

