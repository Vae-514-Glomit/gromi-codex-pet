# Gromi Codex 宠物

这是一个可以放进 Codex 里的 Gromi 小宠物。

Gromi 是一只戴紫色围巾、穿棕色外套的小柯基，胸前有一个琥珀项链。制作时只保留了胸前这一个琥珀，头旁边没有漂浮的琥珀。

![Gromi 预览](previews/contact-sheet.png)

## 怎么下载

点页面右上角绿色的 **Code** 按钮，然后点 **Download ZIP**。

下载后把压缩包解开，你会看到这些重要文件：

- `pet.json`
- `assets/spritesheet.webp`
- `previews` 文件夹，里面是预览图

真正安装宠物只需要前两个文件。

## 怎么安装到 Codex

1. 打开访达。
2. 按下 `Command + Shift + G`。
3. 输入这个位置：

```text
~/.codex/pets/
```

4. 如果里面没有 `gromi` 文件夹，就新建一个，名字叫：

```text
gromi
```

5. 把下载到的两个文件放进去：

```text
pet.json
spritesheet.webp
```

注意：`spritesheet.webp` 在下载包里的 `assets` 文件夹里面。

最后的位置应该像这样：

```text
~/.codex/pets/gromi/pet.json
~/.codex/pets/gromi/spritesheet.webp
```

6. 重新打开 Codex，然后在宠物选择里选择 Gromi。

## 看看效果

待机动画：

![Gromi 待机](previews/idle.gif)

更多动作可以看 `previews` 文件夹。

## 说明

这个项目是给喜欢 Gromi 和 Codex 小宠物的朋友下载使用的。
