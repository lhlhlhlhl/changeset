# GitHub Actions 自动化发布流程测试

这个仓库用于测试 GitHub Actions 自动化发布流程。

## 功能

- 自动创建 "Version Packages" PR
- PR 中包含版本更新和 CHANGELOG 预览
- 合并 PR 后自动发布到 npm

## 测试步骤

1. 创建新的 changeset
2. 提交并推送更改到 main 分支
3. GitHub Actions 自动创建 "Version Packages" PR
4. 检查 PR 中的版本更新和 CHANGELOG 预览
5. 合并 PR，自动发布到 npm