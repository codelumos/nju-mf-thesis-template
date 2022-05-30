# nju-mf-thesis-template

　　本项目提供了一个用于排版南京大学专业硕士学位论文的LaTeX模板。该模板基于[njuHan的模板](https://github.com/njuHan/njuthesis-nju-thesis-template)修改，修复了若干Bug，增加和优化了一些功能细节。

## 使用说明

* 推荐使用 [南京大学在线 LaTeX](https://tex.nju.edu.cn/)（[Overleaf](https://www.overleaf.com/)）直接导入该模板进行写作。
* **必须使用XeLaTeX**。本地推荐安装[MiKTeX](https://miktex.org/)，使用TeXworks编辑，选择**XeLaTeX+MakeIndex+BibTex**编译运行。WinEdt需要使用**UTF-8**编码打开.tex文件，并且使用XeLaTeX编译。
* 使用BibTeX文献管理，用编辑器编辑Thesis.bib文件即可，或使用[JabRef](https://www.jabref.org/)打开。
* 已给出示例文档Thesis.tex，编辑修改该文件即可。默认在Windows系统下使用，若在Mac、Linux操作系统下，需按照Thesis.tex中的注释说明修改参数。

## 文件说明

| 文件/目录 | 说明 |
| --- | --- |
| Thesis.tex | 示例文档，可作为学位论文的基本模板 |
| Thesis.bib | 示例文档的参考文献数据库 |
| njuthesis.cls | 模板类文件 |
| njuthesis.cfg | 模板配置文件 |
| njulogo.eps | 南京大学校徽图片 |
| njuname.eps | 南京大学校名图片 |
| gbt7714-2015.bst | 符合国标 GB/T 7714-2015 的参考文献样式文件 |
| figure/ | 示例文档图片目录 |

## 参考文献格式说明

严格遵循中国国家标准[《GB/T 7714-2015：信息与文献 参考文献著录规则》](https://github.com/codelumos/nju-mf-thesis-template/blob/main/%E3%80%90GB_T%207714-2015%E3%80%91%E4%BF%A1%E6%81%AF%E4%B8%8E%E6%96%87%E7%8C%AE%20%E5%8F%82%E8%80%83%E6%96%87%E7%8C%AE%E8%91%97%E5%BD%95%E8%A7%84%E5%88%99.pdf)
