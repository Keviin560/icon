# Personal Resources

> ⚠️Note: This is a personal asset repository for my configuration. Feel free to fork, but upstream changes may occur without notice.

1024x1024 高清图标合集，源文件托管于 `src/` 目录，通过 GitHub Actions 自动构建索引。

## 项目说明

1. 图片存放：把 `.png` 等图像文件存放在 `src/` 目录。
2. 自动流程：监听 `src/**` 变动，GitHub Actions 变更根目录的 `icon.json` 和 `README.md`。
3. 订阅链接：
   `https://raw.githubusercontent.com/Keviin560/icon/main/icon.json`

---

### 拓扑结构

```text
.
├── src/             # 图标源文件
├── icon.json        # CI 自动生成的标准 JSON 索引
└── .github/         # 自动化工作流脚本
```
