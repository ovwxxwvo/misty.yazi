## Misty Colorful theme for yazi  

迷幻多彩主题。  

![screenshot](screenshot/00.png)  

----  

### 📦 Installation 安装  

The path of the actual config file should be modified according to your own `yazi`.  
The following config file path base on `Arch Linux`.  

实际的配置文件的路径应该根据你自己的 `yazi` 进行修改。  
以下的配置文件的路经基于`Arch Linux`。  

#### Install with package manager 包管理器安装  

```sh  
ya pack -a yazi-rs/flavors:ovwxxwvo/misty  
```  
Add this line to your yazi config file `~/.config/yazi/theme.toml` :  
```toml  
[flavor]  
  use = "misty"  
```  

#### Install manually 手动安装  

Clone the repo to your yazi config dir :  
```sh  
cd ~/.config/yazi/flavors/  
git clone https://github.com/ovwxxwvo/misty.yazi.git  
```  
Add this line to your yazi config file `~/.config/yazi/theme.toml` :  
```toml  
[flavor]  
  use = "misty"  
```  

----  

### 🛠️ Configuration 配置  

Customize your configuration file.  
```sh  
vi ~/.config/yazi/theme.toml  
```  

Or you can just directly modify the config file in the plugin :  
```sh  
vi ~/.config/yazi/flavors/misty.yazi/flavor.toml  
vi ~/.config/yazi/flavors/misty.yazi/tmtheme.xml  
```  

----  

### 📚 Suggestion 建议  

Your app, Your rule. Feel free to modify the files.  
*Another plugin for `tmux`, used to set the bg color.  ([misty.tmux](https://github.com/ovwxxwvo/misty.tmux.git))*  

& some suggestions for settings outside the plugin.  
- Maybe a gray-textured wallpaper will be better fit this.  
- Also a little transparency in the terminal emulator, about 80%|90%.  

& some personal preference settings inside the plugin, change it to your own.  
- dark  skyblue  `#0d141a` as the bg color for  `yazi`.  

你的应用，你说了算。不要害怕修改文件。  

& 一些在插件之外的设定建议。  
- 也许一张灰色纹理的壁纸会更适配。  
- 且一点透明度在终端模拟器中，大约 80%|90%。  

& 一些在插件内部的个人喜好设定，更换为你的喜好。  
- 深天蓝 `#0d141a` 作为  `yazi`  的背景色。  

----  

### 📜 [MIT](LICENSE) License 许可证  


