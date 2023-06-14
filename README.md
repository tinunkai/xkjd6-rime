# 星空键道6
[星空键道6][xkjd6]的[Rime]配置文件。复制`rime`中内容到rime配置路径中部署就行。

## 部署参考
#### Linux
- ibus: `~/.config/ibus/rime/` 0.9.1 以下版本为 `~/.ibus/rime/`
- fcitx: `~/.local/share/fcitx/rime/`
- fcitx5: `~/.local/share/fcitx5/rime/`

Linux手动部署命令参考，在`rime`路径中运行
```
rime_deployer --build . /usr/share/rime-data ./build
```
#### MacOS
- `~/Library/Rime/`
#### Windows
- `%APPDATA%\Rime`

## 冒号emoji功能
类似[特殊符号][tsfh]功能，用冒号`:`引导可以根据名称输入emoji。emoji名称类似[Slack]的简写。

比如键入`:bow`会出现`🙇`等。具体可参考[xkjd6.emoji.dict.yaml][emoji]文件。

## 自定义配置
如需添加预置拓展词库，请编辑 `xkjd6.extended.dict.yaml` ，取消相应注释。

可以在 `xkjd6.user.dict.yaml` 中加入用户自定义词库。

[Rime]: https://rime.im/
[emoji]: https://github.com/tinunkai/xkjd6-rime/blob/main/rime/xkjd6.emoji.dict.yaml
[tsfh]: https://pingshunhuangalex.gitbook.io/rime-xkjd/master-xkjd/extra-symbols
[xkjd6]: https://pingshunhuangalex.gitbook.io/rime-xkjd/
[Slack]: https://slack.com/
