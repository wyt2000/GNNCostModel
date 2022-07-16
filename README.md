# 基于图神经网络的深度学习计算图耗时预测

这是我的本科毕业论文，基于中国科学技术大学的学位论文 LaTeX 模板 [ustcthesis](https://github.com/ustctug/ustcthesis) 编写，
符合 **2021 年 11 月**发布的《[中国科学技术大学本科毕业论文（设计）格式](https://www.teach.ustc.edu.cn/?attachment_id=13867)》标准。

**如需要参考相关格式，请先确认是否与最新发布的毕业论文格式标准一致。**

slides 文件夹内为使用 [ustcbeamer](https://github.com/ustctug/ustcbeamer) 制作的答辩幻灯片，仅供参考。


## 编译文档

- 编译模板的使用说明文档 `ustcthesis-doc.pdf`：
   ```
   latexmk -xelatex ustcthesis-doc.tex
   ```
- 编译论文 `main.pdf`：
   ```
   latexmk -xelatex main.tex
   ```
- 如需清理论文编译过程中的临时文件，可以：
   ```
   latexmk -c
   ```

- 以上编译过程也可以用 `make` 工具：
   ```
   make doc        # 编译生成 ustcthesis-doc.pdf
   make            # 编译生成论文 main.pdf
   make clean      # 删除编译过程中生成的临时文件
   ```
