# html_ft_llm_any_style

LLM 风格调优工具集合，当前包含对话风格调优器与代码风格调优器。

- 在线预览（GitHub Pages）: https://meomeo-dev.github.io/html_ft_llm_any_style/
- 仓库地址: https://github.com/meomeo-dev/html_ft_llm_any_style

## 页面入口

- `index.html`: 工具主页，默认打开对话风格调优器，可切换到代码风格调优器。
- `ft_voice_style.html`: 对话风格调优器。
- `ft_code_style.html`: 代码风格调优器。

## 功能亮点

- 对话风格：40+ 细粒度维度，覆盖立场、结构、情感、指令、质量、安全、风格、认知、意图等分组。
- 代码风格：50 个代码写法维度，覆盖格式、命名、注释、结构、运行标记和测试写法。
- 预设一键应用：快速切换常见工作语境下的风格配置。
- 结果一键复制：生成可复用的 YAML 或连续文本提示词。

## 快速使用

- 在线打开: 直接访问 Pages 链接。
- 本地打开: 克隆仓库后双击 `index.html`。

```bash
git clone https://github.com/meomeo-dev/html_ft_llm_any_style.git
cd html_ft_llm_any_style
open index.html
```

## 部署

本仓库已内置 GitHub Pages 工作流（`.github/workflows/pages.yml`）。

- 将更改推送到 `main` 分支会自动触发部署。
- 部署产物即仓库根目录的静态文件。

## 许可协议

MIT
