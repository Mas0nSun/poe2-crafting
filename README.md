# POE2 Crafting Data

POE2 制作配方数据，支持多语言。

## 仓库结构

```
poe2-crafting/
├── en/
│   └── crafting_recipes.json
├── zh/
    └── crafting_recipes.json
```

## API 访问

### 基础 URL
```
https://raw.githubusercontent.com/yourusername/poe2-crafting/main
```

### 获取数据
```bash
# 获取中文简体数据
curl https://raw.githubusercontent.com/yourusername/poe2-crafting/main/zh/crafting_recipes.json

# 获取英文数据
curl https://raw.githubusercontent.com/yourusername/poe2-crafting/main/en/crafting_recipes.json

```

## 支持的语言

- `en` - English
- `zh` - 简体中文

## 更新数据

1. 修改对应语言文件夹中的 `crafting_recipes.json`
2. 提交到 GitHub
3. 数据会自动更新

## 许可证

MIT License
