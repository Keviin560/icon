# Personal Resources

> ⚠️Note: This is a personal asset repository for my configuration. Feel free to fork, but upstream changes may occur without notice.

1024x1024 高清图标合集，源文件托管于 `src/` 目录，通过 GitHub Actions 自动构建索引分发。

## 项目说明

1. 图片存放：将 `.png` 等支持的图像文件直接推入 `src/` 目录。
2. 自动流程：监听 `src/**` 变动，GitHub Actions 将在短时间内重写根目录的 `icon.json`。
3. 订阅配置：在代理客户端装载以下远程直链：
   `https://raw.githubusercontent.com/<你的用户名>/icon/main/icon.json`

---

### 拓扑结构

```text
.
├── src/             # 图标源文件
├── icon.json        # CI 自动生成的标准 JSON 索引
└── .github/         # 自动化工作流脚本
