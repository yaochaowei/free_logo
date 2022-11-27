# Free Logo V2.0.0

<img src="https://github.com/quarkape/Free_Logo/blob/main/img/free_logo.png" alt="image" style="width:100px" />

一个插件帮你快速、免费下载两个网站的高清LOGO！

---

### :boom:  v2.0.0更新说明

- 现在支持两个在线LOGO设计网站的LOGO下载了，这两个网站在下方👇，点击链接可以直接跳转。

---

### :sunny: 目标网站

- [标小智](https://www.logosc.cn/)
- [标智客](https://www.logomaker.com.cn/)

---

### :leaves: 国内镜像

- [GitHub项目地址](https://github.com/quarkape/free_logo)
- [Gitee项目地址(国内镜像)](https://gitee.com/quarkape/free_logo)

---

### :sailboat: 兼容性

- 经过测试，谷歌浏览器与Edge浏览器可以正常使用

---

### :headphones: 演示视频

- [演示视频(这是v1的演示视频，v2的类似。文字版看下方使用方法)](https://www.bilibili.com/video/BV1t84y1r71B?share_source=copy_web)

---

### :jack_o_lantern: Google Chrome安装方法（Edge差不多）

1. 将完整的项目下载下来
2. 在地址栏输入`chrome://extensions/`（Edge浏览器是`edge://extensions/`）回车，进入扩展程序管理页面
3. 打开开发者模式
4. 页面找到**加载已解压的扩展程序**并点击，选择从本项目即可
5. 加载完成后，在浏览器右上角会出现一个拼图的图标，单击该图标，找到本插件free_logo，点击后面的图钉/眼睛图标可以将该插件固定，使用更便捷。

---

### :badminton: 使用方法

1. 进入目标网站
2. 输入合适的信息，选择合适的LOGO并进入编辑页面
3. （仅标智客会出现）编辑页面会弹出登录框，除非登录，否则无法进入LOGO编辑页面
4. （仅标智客需要用到）打开插件，点击“去除登录框”，会提示去除成功
5. 在编辑页面编辑LOGO直到满意为止
6. 点击插件，在弹出的窗口中输入想要的LOGO的宽度，不输入时取默认值
7. 继续选择是否要保留LOGO背景（默认不保留，即背景为透明，便于转换成.png格式的文件）
8. 配置好后，点击开始处理按钮，即可开始下载svg文件

---

### :hammer_and_wrench: 后续步骤

- 下载下来的free_logo.svg文件可以用PPT直接打开，也能直接用于web中。
- 如果你需要转换成.png格式，可以尝试以下步骤：
  1. 如果你的电脑上还有Internet Explorer，即IE浏览器的话，可以直接将free_logo.svg文件用IE浏览器打开，然后在LOGO上面鼠标右键，另存为，选择格式为.png，选择想要保存的位置（一般是桌面）即可完成。
  2. 如果你电脑上已经没有IE，可以使用Edge的IE模式重新加载页面。首先在Edge中打开free_logo.svg文件，然后点击浏览器右上角用户头像左边的按钮，稍等片刻，Edge浏览器会在IE模式下重新加载页面。加载完成后浏览器工具栏会弹出提醒，此时按照第一步右键另存为.png格式的图片就可以了。
  3. 如果第2步找不到IE模式，请点击右上角三点——设置——默认浏览器，将“允许在 Internet Explorer 模式下重新加载网站”切换为允许，重启浏览器生效，再打开free_logo.svg文件即可。
  4. 如果上述两种方案都无法解决，你可以使用在线的svg转png的方式。不过亲测在线的转换效果比较差。

---

### :palm_tree: 配置说明

- LOGO的大小没必要越大越好，个人认为：
  1. 如果用作网页favicon图标，用68/62就够了
  2. 如果用作一般的网页或者作品的LOGO，用680/620就行了
  3. 如果要用作打印，A4纸大小，小于4000就行了
  4. 如果要打印大的海报，且LOGO占很大面积，可以试试最大6800/6200
- 经过测试，更大的宽度，比如68000/62000，在用IE转换为.png格式的时候会报错“意外的调用了属性或方法”，因此将最大宽度限定于6800/6200。不过应该也够用了。如果有特殊需求的，例如只需要svg文件并且希望更大宽度的，可以单独提issue。当然你也可以自行修改最大宽度，只需要：

  1. 找到`js/content.js`文件并打开
  2. 对于标小智，21行的6800是最大值，修改为你想要的值即可
  3. 对于标智客，28行的6200是最大值，修改为你想要的值即可
  4. 注意修改之后需要在扩展程序管理页面刷新这个插件；或者把这个插件移除了，再重新添加进来。同时记得刷新网页。
- 编辑好的logo一般会居于整个图片中间，可以自行使用PS等工具裁剪。


