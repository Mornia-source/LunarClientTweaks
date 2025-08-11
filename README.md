<h1 align="center">Lunar Client Tweaks（LCT）</h1>

本文档旨在帮助和我一样遇到 Lunar Client 某些不足的玩家，通过外部模组和资源包实现更好的游戏体验。如无特别说明，推荐模组均在1.21 Fabric环境下可用。

---

## 功能性补充

### 1. FreeLook

Lunar Client自带的Freelook功能在部分服务器里被禁止使用，使用模组代替原本Freelook功能。

- **推荐模组**：[FreeLook](https://modrinth.com/mod/freelook)  
- **使用**：在`按键控制`-`按键绑定` 中设置Freelook热键，默认为`左Alt`。)

---

### 2. Auto Text Hot Key

 与Freelook一样，在很多服务器中此功能被禁止使用，但有时又有需要快捷输入经常使用的指令的需求。

<table>
    <tr align="center">
        <td><img src="https://github.com/Mornia-source/LunarClientTweaks/blob/main/Typora%20IMG/LCT-1-2.jpg"></td>
    </tr>
</table>


- **推荐模组**：[Macro Keybinds](https://modrinth.com/mod/macrokeybinds)  

- **使用**：点击热键打开模组菜单进行配置，默认为`N`键。

---

### 3. 潜行动画

在高版本中添加了潜行过渡动画，并修改了潜行时下降的高度，使得原本在1.8.9中应用的搭路等技巧失效，该推荐模组作用是在高版本中还原至1.8.9时的潜行动画。

- **推荐模组**：[Sneakie Lite 1.8](https://modrinth.com/mod/sneakie-like-1.8)  

- **使用**：无需任何配置，安装完成进入游戏点按`Shift`查看效果即可。

---

### 4. Crosshair 

Lunar Client自带Crosshair功能较少且单一，可配置项不多，使用模组代替Lunar Client原本的Crosshair功能，提供高度自定义的准星设计（颜色、形状、大小等）。

- **推荐模组**：[Custom Crosshair Mod](https://modrinth.com/mod/custom-crosshair-mod)  

- **使用**：点击热键打开模组菜单进行配置，默认为`` ` ``键（通常在主键盘`数字1`旁边）。

---

### 5. 资源包：缩小手持物品

Lunar Client不支持修改手持显示物品大小，这会占用额外的屏幕显示位置。该资源包缩小效果约等于Badlion Client中0.5物品大小。

<table>
    <tr align="center">
        <td><img src="https://github.com/Mornia-source/LunarClientTweaks/blob/main/Typora%20IMG/LCT-1-5.jpg"></td>
    </tr>
</table>


- **推荐资源包**：[Small Held Items](https://modrinth.com/resourcepack/small-held-items)  

- **使用**：将资源包 `.zip` 放入 `.minecraft/resourcepacks/` 文件夹，游戏内启用即可。

---

### 6. 敌人血量显示

Lunar Client不支持修改手持显示物品大小，这会占用额外的屏幕显示位置。该资源包缩小效果约等于Badlion Client中0.5物品大小。

<table>
    <tr align="center">
        <td><img src="https://github.com/Mornia-source/LunarClientTweaks/blob/main/Typora%20IMG/LCT-1-6.jpg"></td>
    </tr>
</table>


- **推荐模组**：[Health Indicator](https://modrinth.com/datapack/health-indicator)  
- **使用**：无需任何配置，安装完成进入游戏查看效果即可。

---

### 7. 自身低血量提示

当你的健康值低于某个指定的数值时，会在屏幕上显示警告，并给予提示音（可选）。

- **推荐模组**：[HealthIndicator](https://modrinth.com/mod/healthindicator)  
- **使用**：点击热键或通过Mod Menu打开模组菜单进行配置。

---

## 辅助类模组

### 1. 模组按键冲突管理

模组数量多起来时，会出现很多不必要的重复热键，其中因部分模组处理优先级较高，如果不修改按键操作，则会产生很多不必要的麻烦。

> [!TIP]
>
> <font color="#1f883d"><strong>Minecraft原版中设置热键为空的操作为，先单击按键，使其处于响应状态，再按`ESC`键。</strong></font>

- **推荐模组**：[Controlling](https://modrinth.com/mod/controlling)
- **使用**：放入 `mods` 文件夹，游戏启动后在设置界面查看使用。

### 2. 自定义披风显示

众所周知，MC的披风价格一直炒着比较高，而实际测试过后发现，即便你真的有某些稀有披风，在服务器中也并不会因此多一两个人询问你甚至申请好友，更多的是一种给予自身的娱乐。该模组的显示效果在多人游戏中仅自己可见。

- **推荐模组**：[Capes | Better Capes](https://modrinth.com/mod/better-capes-x)  
- **使用**：放入 `mods` 文件夹，游戏启动后点击热键打开模组菜单进行使用，默认为`N`键。

---

## 部分问题汇总

### 1. 模组缺少前置

<table>
    <tr align="center">
        <td><img src="https://github.com/Mornia-source/LunarClientTweaks/blob/main/Typora%20IMG/LCT-3-1.jpg" width="400px"></td>
    </tr>
</table>


出现如上因缺少模组对应前置导致的启动失败报错时，点击模组名称后的放大镜按钮可跳转到`Curseforge`或`Modrinth`的模组下载页面进行下载。

如无您所需要版本对应功能的Mod，请及时反馈。
