# ykx-tslint

基于 AlloyTeam 的 [`tslint-config-alloy`](https://github.com/AlloyTeam/tslint-config-alloy) 修改的个性化规则。方便在新建项目时不用反复的去复制黏贴配置文件。每一条规则都会有相关的注释以便理解。之后会将相关注释转移到 `README.md` 中，并添加每条规则相关的例子方便理解。

## 如何使用

在你的项目中安装 `ykx-tslint`。

```bash
yarn add ykx-tslint --dev --exact
```

在你的 `tslint.json` 文件中添加如下代码：

```json
{
  "extends": ["ykx-tslint"],
  "rules": {
    // 根据不同项目可以改变特定的规则
    // ...
  }
}
```