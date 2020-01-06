
# gnome-theme-macos

![](/images/3.png)

## 部署方法

```shell
git clone https://github.com/tcbaby/gnome-beautify.git
cd gnome-beautify
chmod +x install.sh && ./install.sh
```

## 设置方法

部署完成后，按下ALT+F2输入r重新加载桌面，然后打开Tweaks-tool进行设置

![](/images/1.png)
![](/images/2.png)

打开Dash to Dock设置Dash位置、图标大小等

## gnome桌面

gnome主题/图标下载： <https://www.gnome-look.org/>

gnome拓展插件下载： <https://extensions.gnome.org/>

### 图标/主题文件位置

```shell
# 主题
/usr/share/themes       # 全局       
~/.themes		        # 用户

# 软件图标/光标样式
/usr/share/icons
~/.icons

# gnome extensions
/usr/share/gnome-shell/extensions/
~/.local/share/gnome-shell/extensions/

# 桌面图标
/usr/share/applications/
~/.local/share/applications/
```

### gnome拓展

- 安装方法
    1. 通过linux下的包管理工具,安装`gnome-shell-extensions-插件名`
    2. 直接下载源码到指定的目录
    3. 通过浏览器插件安装
        1. 使用firefox/chrome进到[官方网站](https://extensions.gnome.org), 根据提示安装浏览器插件
        2. 在[官方网站](https://extensions.gnome.org), 搜索需要的拓展安装即可

- 好用的拓展
    - dash to dock 
    - user theme                 开启shell主题自定义设置      
    - Topicons / Topiconsfix     顶栏托盘 
    - places status indicator    顶栏目录菜单       
    - netspeed                   顶栏显示网速
    - system-monitor             系统监控
    - cpupower / cpufreq         处理器调频控制
    - caffeine                   阻止桌面锁屏和系统暂停
    - workspace-indicator         显示工作区序号
    - top-panel-workspace-scroll  顶部栏上滚动鼠标切换工作区
    - pixel-saver                 窗口最大化时将标题栏融入顶部pannel
    - VSCode Search Provider      搜索vscode最近项目
    - Drop down terminal          下拉终端
    - gsconnect                   与手机kdeconnect连接
    - Extensions Sync:            gnome extensions备份