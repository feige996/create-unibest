# 调试

- pnpm build
- pnpm dev

## link 调试
- npm link
- create-unibest xx -t base
- create-unibest xx2

## 发布
因为已经有 github action，所以不需要手动发布，只需要修改版本号即可，并打tag然后推送到github 即可。

```bash
# 先更新版本号
npm version patch  # 或 minor/major

# 创建并推送tag（格式必须为v开头）
git tag v1.x.x
git push origin v1.x.x
```    