# ⚡ Performance Tools

AI前端性能工具，支持性能审计、优化建议、代码分割。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 📊 性能审计
- 🖼️ 图片优化建议
- 📦 代码分割建议
- 🔄 Service Worker生成
- 📈 Web Vitals优化

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from perf_tools import create_tools

tools = create_tools()

# 性能审计
audit = tools.audit_performance({"FCP": "2.5s", "LCP": "4.0s"})

# 图片优化
images = tools.optimize_images(image_list)

# 代码分割
splitting = tools.suggest_code_splitting(bundle_analysis)

# Service Worker
sw = tools.generate_service_worker("network-first")

# Web Vitals
vitals = tools.generate_web_vitals_optimization({"LCP": "4.0s"})
```

## 📁 项目结构

```
perf-tools/
├── tools.py       # 性能工具核心
└── README.md
```

## 📄 许可证

MIT License
