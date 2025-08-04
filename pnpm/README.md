# Hey Pnpm 100

|本期版本|上期版本
|:---:|:---:
`Wed May 14 11:48:37 CST 2025` | -

```bash
npm install pnpm -g
```

## 获取当前活跃的store目录

```bash
# ~/Library/pnpm/store/v10
pnpm store path
```

## 自定义 store目录

```bash
mkdir -p /Volumes/THAWSPACE/.pnpm/store/v10
pnpm config set store-dir /Volumes/THAWSPACE/.pnpm/store/v10
```

## 安装全局依赖


```bash
set -gx PNPM_HOME ~/Library/pnpm
fish_add_path  $PNPM_HOME
```

```bash
pnpm add -g lodash
pnpm create vite
```



## Ref

* <https://pnpm.io/>
* <https://pnpm.io/zh>