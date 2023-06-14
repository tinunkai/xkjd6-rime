# 星空键道6

星空键道6 rime 配置文件。复制`rime`中内容到rime配置路径中部署就行。

Linux

- ibus: `~/.config/ibus/rime/` 0.9.1 以下版本为 `~/.ibus/rime/`
- fcitx: `~/.local/share/fcitx/rime/`
- fcitx5: `~/.local/share/fcitx5/rime/`

Linux手动部署命令参考，在`rime`路径中运行
```
rime_deployer --build . /usr/share/rime-data ./build
```

MacOS

- `~/Library/Rime/`

Windows

- `%APPDATA%\Rime`

如需添加词库，请编辑`xkjd6.extended.dict.yaml`，取消相应注释。

可以在`xkjd6.user.dict.yaml`中加入用户自定义词库。
