# Global AI Legal Risk Tracker

全球AI法律风险追踪项目 - 网站发布包

## 项目说明

本项目系统性追踪和分析全球范围内与人工智能相关的法律风险，包括：
- 立法与法规更新 (Legislation & Regulations Updates)
- 诉讼与执法动态 (Litigation & Enforcement)

## 优先级分类

| 级别 | 名称 | 关注重点 |
|------|------|----------|
| P0 | 最高优先级 | 欧盟/美国出口管制、制裁、实体清单 |
| P1 | 高优先级 | 重大AI立法、高额罚款、里程碑判决 |
| P2 | 标准优先级 | 常规法规更新、草案、一般执法动态 |

## 更新频率

**每周五 北京时间 18:00 (UTC+8)** 定期更新

## 部署到 GitHub Pages

### 方法一：直接上传

1. 创建新的 GitHub 仓库
2. 将 `website/` 目录中的内容上传到仓库根目录
3. 进入仓库 Settings → Pages
4. Source 选择 "Deploy from a branch"
5. Branch 选择 "main" 分支，文件夹选择 "/ (root)"
6. 保存后等待几分钟即可访问

### 方法二：使用 Git 命令

```bash
cd website
git init
git add .
git commit -m "Initial commit: AI Legal Risk Tracker"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

然后在 GitHub 仓库设置中启用 Pages。

## 文件结构

```
website/
├── index.html          # 主页面（包含所有样式和脚本）
└── README.md           # 本说明文件

archives/               # 历史报告归档
└── 2026/
    └── 01/
        └── ...
```

## 自定义域名（可选）

如需使用自定义域名：
1. 在仓库根目录创建 `CNAME` 文件
2. 写入你的域名，如 `tracker.example.com`
3. 在域名 DNS 设置中添加 CNAME 记录指向 `YOUR_USERNAME.github.io`

## 许可证

本项目仅供参考，非法律意见。

---

Created by Matrix Agent | 每周五 18:00 北京时间更新
