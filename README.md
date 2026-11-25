<p align="center">
  <strong>简体中文</strong> | <a href="./README_EN.md">English</a>
</p>

<div align="center">

# Academic Paper LaTeX Templates（主流学术期刊 LaTeX 论文模板合集）

**一站式整理 Elsevier、IEEE Transactions、Springer Nature、MDPI、Frontiers of Computer Science 等 8 套主流 SCI / EI 期刊官方 LaTeX 模板，开箱即用**

![LaTeX](https://img.shields.io/badge/LaTeX-TeX_Live_%2F_Overleaf-008080?style=flat-square&logo=latex&logoColor=white)
![Templates](https://img.shields.io/badge/Templates-8_Journals_%26_Publishers-6366f1?style=flat-square)

</div>

---

## 模板清单

| 目录 | 出版社 / 期刊 | 核心类文件 (`.cls`) | 主示例文件 |
| :--- | :--- | :--- | :--- |
| `IEEE-Transactions-LaTeX2e-templates-and-instructions/` | **IEEE Transactions** 系列期刊 | `IEEEtran.cls` | `bare_jrnl_new_sample4.tex` |
| `els-cas-templates/` | **Elsevier CAS**（单/双栏现代模板） | `cas-sc.cls` / `cas-dc.cls` | `cas-sc-template.tex` / `cas-dc-template.tex` |
| `elsarticle/` | **Elsevier** 标准 `elsarticle` 模板（如 *Measurement* 等） | `elsarticle.cls` / `.dtx` | `elsarticle-template-num.tex` |
| `sn-article-template/` | **Springer Nature** 新版通用模板 | `sn-jnl.cls` | `sn-article.tex` |
| `Springer LaTeX Template/` | **Springer** 经典 `svjour3` 模板（如 *Autonomous Robots* 等） | `svjour3.cls` | `template.tex` |
| `FCS LaTeX Template/` | **Frontiers of Computer Science**（完整官方版） | `fcs.cls` | `template.tex` |
| `Frontiers_of_computer_science/` | **Frontiers of Computer Science**（精简版） | `fcs.cls` | `template.tex` |
| `MDPI_template_ACS/` | **MDPI** 期刊系列模板 | `Definitions/mdpi.cls` | `template.tex` |

## 使用方式

1. **本地编译（推荐 TeX Live + `latexmk`）**：
   ```bash
   cd <template-directory>
   latexmk -pdf <main-template>.tex
   ```
2. **Overleaf 在线使用**：将对应子目录打包为 `.zip` 后直接上传至 Overleaf 即可一键编译。

> 注：所有模板均已清理本地编译临时文件（`.log`、`.aux`、`.synctex`），版权归对应出版社与官方维护者所有，仅用于学术写作与投稿排版参考。
