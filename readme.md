
---
初始化 [obsidian vault](https://github.com/lx-obsidian/obsidian-vault) （仅含插件和代码段等内容的初始 vault）

```bash
git clone --depth=1 -b config git@github.com:lx-obsidian/obsidian-vault ob
cd ob
git clone --depth=1 git@github.com:lx-obsidian/plugins .obsidian/plugins

rmdir .git /s /q
rmdir ".obsidian/plugins/.git" /s /q
```

