# 2026 小学语文教资面试 · 24天零基础冲刺手册

无需安装任何依赖。打开 `index.html` 即可浏览；上传到 GitHub Pages 后即可在线访问。

## 功能

- 左侧固定目录，点击跳转章节；移动端显示折叠目录
- 官方流程、六类课型、结构化问答、教案模板、24天学习计划、考前检查清单
- 每日打卡、进度条和“仅看未完成”（使用浏览器 localStorage 保存，不跨设备同步）
- 复制教案模板、复制网页地址、打印或另存为 PDF
- 全页面适配电脑和手机，无第三方 CDN 或外链脚本，支持离线使用

## GitHub Pages 部署（网页操作方式）

1. 登录 [GitHub](https://github.com/new)，新建一个 **Public** 仓库。例如 `primary-chinese-interview-2026`。
2. 在仓库首页选择 **Add file → Upload files**，上传 `index.html`，提交到 `main` 分支。（可一并上传本 README 和 `.nojekyll`。）
3. 打开仓库 **Settings → Pages → Build and deployment**，在 **Source** 中选择 **Deploy from a branch**，分支选 **main**，文件夹选 **/(root)**，保存。
4. 部署完成后在 Pages 设置页查看页面地址。个人仓库通常形如：`https://<GitHub用户名>.github.io/primary-chinese-interview-2026/`。具体地址以 GitHub Pages 实际显示为准。

> GitHub Pages 发布后，网站为公开访问，当前页面不包含个人隐私信息。打卡数据只存储在访客自己的浏览器中。

## 另一种部署方式：命令行

```bash
git init
git add index.html README.md .nojekyll
git commit -m "Add interview preparation guide"
git branch -M main
git remote add origin https://github.com/<GitHub用户名>/primary-chinese-interview-2026.git
git push -u origin main
```

随后同样在 GitHub 的 **Settings → Pages** 中启用 `main` 分支发布。

## 页面来源与准确性

- [福建省教育考试院关于举行2026年下半年中小学教师资格考试（面试）的公告](https://www.fuzhou.gov.cn/zgfzzt/jy/ksxx/zxksshksxx/202610/t20261030_5387994.htm)
- [中国教育考试网：参加面试的流程](https://ntce.neea.edu.cn/xhtml1/report/2307/285-1.htm)

面试实际日期、考点与要求请以本人准考证及官方最新通知为准。课型示例及时间分配是备考建议，不是官方押题。
