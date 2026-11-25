<p align="center">
  <a href="./README.md">简体中文</a> | <strong>English</strong>
</p>

<div align="center">

# Academic Paper LaTeX Templates

**A Curated, Clean Collection of 8 Official LaTeX Manuscript Templates for IEEE Transactions, Elsevier, Springer Nature, MDPI, and Frontiers of Computer Science**

![LaTeX](https://img.shields.io/badge/LaTeX-TeX_Live_%2F_Overleaf-008080?style=flat-square&logo=latex&logoColor=white)
![Templates](https://img.shields.io/badge/Templates-8_Journals_%26_Publishers-6366f1?style=flat-square)

</div>

---

## Included Templates

| Directory | Publisher / Journal | Class File (`.cls`) | Main Entry File |
| :--- | :--- | :--- | :--- |
| `IEEE-Transactions-LaTeX2e-templates-and-instructions/` | **IEEE Transactions** Journals | `IEEEtran.cls` | `bare_jrnl_new_sample4.tex` |
| `els-cas-templates/` | **Elsevier CAS** (Single / Double Column) | `cas-sc.cls` / `cas-dc.cls` | `cas-sc-template.tex` / `cas-dc-template.tex` |
| `elsarticle/` | **Elsevier** Standard `elsarticle` (e.g., *Measurement*) | `elsarticle.cls` / `.dtx` | `elsarticle-template-num.tex` |
| `sn-article-template/` | **Springer Nature** Unified Journal Template | `sn-jnl.cls` | `sn-article.tex` |
| `Springer LaTeX Template/` | **Springer** Classic `svjour3` (e.g., *Autonomous Robots*) | `svjour3.cls` | `template.tex` |
| `FCS LaTeX Template/` | **Frontiers of Computer Science** (Full Official) | `fcs.cls` | `template.tex` |
| `Frontiers_of_computer_science/` | **Frontiers of Computer Science** (Compact) | `fcs.cls` | `template.tex` |
| `MDPI_template_ACS/` | **MDPI** Journals | `Definitions/mdpi.cls` | `template.tex` |

## Usage

```bash
cd <template-directory>
latexmk -pdf <main-template>.tex
```

Or zip any template directory and upload directly to **Overleaf**.

> All temporary build artifacts (`.log`, `.aux`, `.synctex`) have been stripped. Original template copyrights belong to their respective publishers.
