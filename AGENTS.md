## 构建与测试
- **安装依赖**: `npm install`
- **运行测试**: `npm test`

## 代码风格
- 使用 TypeScript，并启用严格模式（strict mode）。

## 通用边界与安全
- **禁止提交**: 任何情况下都不要提交包含 secrets 或 API keys 的代码。
- **禁止修改目录**: 严禁改动 `node_modules/` 目录下的任何文件。
- **提交前检查**: 在提交任何代码更改之前，必须确保 lint 和测试全部通过。
