# eslint-config-vue

## Install

```bash
pnpm add eslint @lxchapu/eslint-config-vue -D
```

## Usage

在你的 eslint 配置文件中添加以下内容：

```js
{
  extends: ["@lxchapu/eslint-config-vue"]
}
```

在 `package.json` 中添加脚本：

```json
{
  "lint": "eslint --fix src/**/*.{js,ts,tsx,vue}"
}
```

## Lincense

MIT
