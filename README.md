# Xiaoou Ding | 丁小欧

Associate Professor and Ph.D. supervisor at the Faculty of Computing, Harbin Institute of Technology.

<p>
  <a href="https://dx0o0.github.io/"><img alt="Homepage" src="https://img.shields.io/badge/Homepage-dx0o0.github.io-0f766e?style=flat-square"></a>
  <a href="mailto:dingxiaoou@hit.edu.cn"><img alt="Email" src="https://img.shields.io/badge/Email-dingxiaoou%40hit.edu.cn-374151?style=flat-square"></a>
  <a href="https://homepage.hit.edu.cn/dingxiaoou"><img alt="HIT Profile" src="https://img.shields.io/badge/HIT-Official%20Profile-2563eb?style=flat-square"></a>
  <a href="https://dblp.org/pid/168/4671"><img alt="DBLP" src="https://img.shields.io/badge/DBLP-168%2F4671-b7791f?style=flat-square"></a>
</p>

## About

丁小欧，哈尔滨工业大学计算学部副教授、博士生导师。研究方向包括大数据治理、数据质量管理、面向机器学习的高质量数据构建，以及工业物联网时序数据治理与分析。

Xiaoou Ding is an Associate Professor and Ph.D. supervisor at the Faculty of Computing, Harbin Institute of Technology. Her research covers big data governance, data quality management, high-quality data construction for machine learning, and industrial IoT time-series data governance and analytics.

## Research

- Big data governance and data-asset value
- Data quality assessment, error detection, repair, and cleaning systems
- High-quality data construction for machine learning
- Industrial IoT time-series data governance and analytics

## Selected Recent Publications

| Year | Venue | Publication |
| --- | --- | --- |
| 2026 | ICML | DMCO: Budget-Aware Co-Optimization of Data Cleaning and AutoML |
| 2026 | ICDE | PROCore: Robust Core-set Selection via Pareto Multi-dimensional Optimization from Noisy Data |
| 2026 | VLDB Demo | MAPPipe: A System of Data Preprocessing Pipeline Optimization via Structural Pruning and Knowledge-augmented MCTS |
| 2026 | IEEE TKDE | FinePar: A Fine-Grained Data Partitioning Framework for Cloud-Edge-Device Architectures |
| 2025 | PVLDB | bNDCRepair: Cleaning both Data Errors and Inaccurate Constraints on Numerical Sequential Data |
| 2025 | PVLDB | UniClean: A Scalable Data Cleaning Solution for Mixed Errors based on Unified Cleaners and Optimized Cleaning Workflow |
| 2025 | ICDE | tDCDiscover: Mining Threshold Denial Constraints from Time Series Data |
| 2025 | BDMA | A Survey on Data Asset Value Change Estimation and Appreciation with Data Governance |

The complete publication record is available on [DBLP](https://dblp.org/pid/168/4671).

## Website

- `index.html`: detailed bilingual academic homepage
- `snapshot.html`: concise bilingual profile
- `styles.css` and `snapshot.css`: responsive styles
- `script.js`: language switching and hero animation

Run a local preview from the repository root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

Public pages intentionally omit the phone number, date of birth, exact office room, project budgets, grant identifiers, and certificate identifiers from the source CV.

## 换电脑维护

维护约定保存在 [AGENTS.md](AGENTS.md)，与网站源码一起通过 Git 同步。请将该仓库作为两台电脑间的交接依据；聊天记录和本机文件不会随 Git 自动同步。

### 新电脑首次使用

安装 Git，在自己选择的目录中运行：

```sh
git clone https://github.com/dx0o0/dx0o0.github.io.git
cd dx0o0.github.io
```

打开这个克隆下来的文件夹，并先阅读 `AGENTS.md`。提交时配置维护者本人的身份，推送时使用有该仓库写入权限的 GitHub 账号；不要照抄历史提交者信息，也不要把登录令牌放进仓库。

```sh
git config user.name "你的名字"
git config user.email "你的提交邮箱"
```

上述身份设置仅作用于当前仓库，不代表已登录 GitHub。

### 每次开始与结束

开始前检查是否有本地修改；工作区干净时拉取最新版本：

```sh
git status --short --branch
git pull --ff-only
```

完成后检查差异，只暂存本次修改的文件，提交并推送到 `main`。换电脑前确认没有需要带走但尚未提交或推送的工作。另一台电脑也应先拉取，再编辑；尽量避免两台电脑同时修改同一文件。遇到冲突或分叉时先保留双方修改并检查差异，不使用强制推送或重置来覆盖。

页面更新推送后，在 GitHub Actions 中查看对应提交的 Pages 部署是否成功，再打开线上主页核验。浏览器仍显示旧内容时可按 `Ctrl + F5` 强制刷新。

### 本地预览

本项目没有 Node.js 构建依赖。安装 Python 后可在仓库根目录启动预览：Windows 使用 `py -m http.server 8000`，其他系统通常使用 `python3 -m http.server 8000`。随后打开 `http://localhost:8000/`，结束时按 `Ctrl + C` 停止服务。
