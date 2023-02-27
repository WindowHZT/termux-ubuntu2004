# termux-ubuntu2004

- [x] Ubuntu 20.04
- [x] XFCE4 Desktop
- [x] TigerVNC Server，Xrdp
- [x] Non-root Account Creation
- [x] Audio Support
- [x] The following can be custom installed：
- ***Browser***： \
				 &emsp;Chromium \
				&emsp;FireFox
- ***The development tools***： \
				&emsp;IntelliJ IDEA \
				&emsp;VSCode \
				&emsp;Eclipse \
				&emsp;Android Studio \
				&emsp;PyCharm
- ***Office software***： \
				&emsp;WPS office
- ***Chinese input method***： \
				&emsp;Google pinyin \
				&emsp;Fcitx pinyin \
				&emsp;搜狗输入法 （功能测试中）
- ***Desktop beautification***： \
				&emsp;Background \
				&emsp;Themes \
				&emsp;Software ICONS \
				&emsp;The cursor ICONS
				
### 1）Installation
Copy and paste this command to Termux:
复制以下命令到 Termux 执行
```bash
bash -c "$(curl -L raw.githubusercontent.com/WindowHZT/termux-ubuntu2004/main/ubuntu20)"
```



# Some screenshots


```mermaid

graph TD

    A[开始] --> B[设置画笔颜色为黄色和背景色为黑色，笔宽为10];

    B --> C[初始化循环计数器a=0];

    C --> D[判断循环条件a<100];

    D --> |是| E[将画笔抬起，随机移动到一个位置];

    E --> F[将画笔放下，初始化内部循环计数器i=0];

    F --> G[判断循环条件i<5];

    G --> |是| H[向前移动15个单位，向左转144度];

    H --> I[将内部循环计数器i+1];

    I --> J[返回G继续判断循环条件];

    G --> |否| K[返回E继续绘制下一个五角星];

    D --> |否| L[结束

```


