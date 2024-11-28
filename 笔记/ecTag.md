ecTag 是一种基于 CRISPR 技术的 DNA 标记方法，用于在活细胞中追踪细胞外 DNA（[[ecDNA]]）。其原理及方法如下：

### 原理

  

- **利用 ecDNA 特异性断点序列**：ecDNA 是由 DNA 断裂后末端连接形成，其断点序列在亲本线性染色体中不存在。通过设计针对这些独特断点序列的单引导 RNA（sgRNA），可以特异性地标记 ecDNA1。

### 方法

  

1. **设计 sgRNA**
    - 分析全基因组测序（WGS）数据，确定 ecDNA 的结构和断点序列，针对这些断点设计带有可编程 Pumilio/FBF（PUF）RNA 结合位点（PUFBSs）的 sgRNA。这些 sgRNA 的间隔序列（spacer sequence）与 ecDNA 断点序列互补，使其能够特异性结合到 ecDNA 上12。
    - 设计了四个针对 HF3016 神经球细胞系中不同 ecDNA 结构（包含 EGFR 片段、CCAT 和 CCDC26 等）的 sgRNA，分别标记为 ecEGFRx1、ecEGFR、ecCCAT1 和 ecCCDC261。
2. **构建 ecTag 系统**
    - 采用 [[Casilio]] 技术，将催化失活的 Cas9（dCas9）与 PUF 融合蛋白（Clover-PUF）结合。sgRNA 引导 dCas9-Clover-PUF 复合物结合到 ecDNA 的断点位点，从而招募多个荧光蛋白分子（Clover），实现对 ecDNA 的标记13。
3. **实验验证**
    - **体外切割实验**：对 HF3016 和 HF3177 细胞进行体外切割实验，以验证 sgRNA 的靶向效率，确保其能够准确地结合到目标 ecDNA 断点上3。
    - **细胞转染与分析**
        - 将 sgRNA、dCas9 和 Clover-PUF 表达质粒共转染到细胞中（如 HF3016、HF3177 和 PC3 细胞系），通过荧光显微镜观察细胞中的荧光信号，确定 ecTag 的靶向特异性和效率4。
        - 进行双色成像实验，如将 DNA-FISH 与 ecTag ecDNA 标记相结合，评估 ecTag 信号与特定 ecDNA 断点的映射准确性，以及与染色体对照（Chr7 和 MUC4）的靶向效率对比5。
        - 通过对 EGFR 靶向的 ecTag 转染的 HF3016 细胞进行 EGFR DNA FISH 实验，进一步验证 ecTag 检测 ecDNA 的能力，并分析 ecTag 信号与 FISH 信号之间的关系5。
4. **活细胞成像与分析**
    - 对转染 ecTag 的细胞进行活细胞成像，观察 ecDNA 在细胞分裂过程中的动态行为，包括在有丝分裂期间的稀释和重新分布，以及在分裂后的聚集形成 ecDNA 枢纽67。
    - 利用多种技术手段，如逐步光漂白实验、双色 ecTag 标记实验等，分析 ecDNA 信号的特征（如信号大小、分子组成等），以及 ecDNA 之间的相互作用和聚集行为7811。
5. **与其他分子的共定位分析**
    - 通过免疫荧光染色，将 ecTag 转染细胞与核体（如 Cajal 体和 PML 核体）或 RNA 聚合酶 II（RNAPII）的标记抗体共染，然后进行荧光显微镜观察和共定位分析，评估 ecDNA 与这些分子之间的相互作用和共定位关系，以探究 ecDNA 枢纽在基因转录中的作用9102。

  

ecTag 方法通过巧妙利用 ecDNA 特异性断点序列和 CRISPR-Casilio 技术，实现了在活细胞中对 ecDNA 的动态追踪和分析，为研究 ecDNA 在肿瘤细胞中的生物学行为提供了有力工具。