## eslint
`eslint`，对代码不仅有风格的校验，更有可读性、安全性、健壮性的校验

### Rule
在 `eslint` 中，使用 `Rule` 最为校验代码最小规则单元
### Plugin
如 `react`、`typescript`、`flow` 等，需要自制 `Rule`，此类为 `Plugin`
在命名时以 `eslint-plugin-` 开头并发布在 `npm` 仓库中
### Config
在第三方库、公司业务项目中需要配置各种适应自身的规则、插件等，称为 `Config`
1.  作为库发布，在命名时以 `elint-config-` 开头，并发布在 `npm` 仓库中。
2.  为项目服务，在项目中以 `.eslintrc` 命名或者置于项目 package.json 中的 `eslintConfig` 字段中，推荐第二种方案。