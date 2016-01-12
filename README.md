**Analyzing the Impact of Heterogeneous Blocks on FPGA Placement Quality**

Chang Xu, Guojie Luo, Peking University, {changxu, gluo}@pku.edu.cn

In this project we propose a quantitative approach to analyze the impact of heterogeneous blocks (H-blocks) on the FPGA placement quality. The basic idea is to construct synthetic heterogeneous placement benchmarks with known optimal wirelength to facilitate the quantitative analysis. Besides analyzing the quality of existing placers (VPR and Quartus), we further decompose the impacts of H-blocks from the architectural aspect and netlist aspect. Our analysis shows that a heterogeneous design hides the wirelength degradation by a more compact netlist than its homogeneous version; however, the heterogeneity results in a optimality gap of 52% in wirelength, where 25% is from architectural heterogeneity and 27% is from netlist heterogeneity. We release heterogeneous synthetic benchmarks (in VPR format and Altera VQM format) to help researchers and developers of heteregeneous FPGA placers to better understand the quality of their placers in handling the architectural heterogeneity and netlist heterogeneity separately.

This work is parly supported by National Natural Science Foundation of China (NSFC) Grant 61202073, Research Fund for the Doctoral Program of Higher Education of China (MoE/RFDP) Grant 20120001120124, and Beijing Natural Science Foundation (BJNSF).

[1] Xu, Chang, Wentai Zhang, and Guojie Luo. "Analyzing the impact of heterogeneous blocks on FPGA placement quality." Field-Programmable Technology (FPT), 2014 International Conference on. IEEE, 2014.
