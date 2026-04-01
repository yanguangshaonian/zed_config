```shell


# 1. 把现有的文件重命名备份一下
mv ~/.config/zed/settings.json ~/.config/zed/settings.json.bak 2>/dev/null || true
mv ~/.config/zed/tasks.json ~/.config/zed/tasks.json.bak 2>/dev/null || true
mv ~/.config/zed/keymap.json ~/.config/zed/keymap.json.bak 2>/dev/null || true

# 2. 为具体的配置文件创建软链接
ln -s /Users/yanguangshaonian/Documents/zed_config/settings.json ~/.config/zed/settings.json
ln -s /Users/yanguangshaonian/Documents/zed_config/tasks.json ~/.config/zed/tasks.json
ln -s /Users/yanguangshaonian/Documents/zed_config/keymap.json ~/.config/zed/keymap.json


```
