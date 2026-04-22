# Yarn

> Rails 项目还需要使用该工具

|本期版本|上期版本
|:---:|:---:
`Wed Apr 22 17:43:21 CST 2026` | `Tue Aug  8 13:22:33 CST 2023`

## macOS

```bash
brew install yarn
```

## Debian / Ubuntu

```bash
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | gpg --dearmor | sudo tee /etc/apt/keyrings/yarn-archive-keyring.gpg > /dev/null
echo "deb [signed-by=/etc/apt/keyrings/yarn-archive-keyring.gpg] https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
```


```bash
yarn config set registry https://registry.npmmirror.com
```



## Ref

* <https://classic.yarnpkg.com/>