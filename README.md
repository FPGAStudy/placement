**Analyzing the Impact of Heterogeneous Blocks on FPGA Placement Quality**

Chang Xu, Guojie Luo, Peking University, {changxu, gluo}@pku.edu.cn

In this project we propose a quantitative approach to analyze the impact of heterogeneous blocks (H-blocks) on the FPGA placement quality. The basic idea is to construct synthetic heterogeneous placement benchmarks with known optimal wirelength to facilitate the quantitative analysis. Besides analyzing the quality of existing placers (VPR and Quartus), we further decompose the impacts of H-blocks from the architectural aspect and netlist aspect. Our analysis shows that a heterogeneous design hides the wirelength degradation by a more compact netlist than its homogeneous version; however, the heterogeneity results in a optimality gap of 52% in wirelength, where 25% is from architectural heterogeneity and 27% is from netlist heterogeneity. We release heterogeneous synthetic benchmarks (in VPR format and Altera VQM format) to help researchers and developers of heteregeneous FPGA placers to better understand the quality of their placers in handling the architectural heterogeneity and netlist heterogeneity separately.

This work is parly supported by National Natural Science Foundation of China (NSFC) Grant 61202073, Research Fund for the Doctoral Program of Higher Education of China (MoE/RFDP) Grant 20120001120124, and Beijing Natural Science Foundation (BJNSF).

References

[1] V. Betz and J. Rose, “Vpr: A new packing, placement and routing tool for fpga research,” in Proceedings of the 7th International Workshop on Field-Programmable Logic and Applications, ser. FPL ’97. London, UK, UK: Springer-Verlag, 1997, pp. 213–222. 

[2] P. Maidee, C. Ababei, and K. Bazargan, “Timing-driven partitioningbased placement for island style fpgas,” Computer-Aided Design of Integrated Circuits and Systems, IEEE Transactions on, vol. 24, no. 3, pp. 395–406, March 2005.

[3] M. J. Alexander, J. P. Cohoon, J. L. Ganley, and G. Robins, “Placement and routing for performance-oriented fpga layout.”

[4] M. Gort and J. Anderson, “Analytical placement for heterogeneous fpgas,” in Field Programmable Logic and Applications (FPL), 2012 22nd International Conference on, Aug 2012, pp. 143–150.

[5] T.-H. Lin, P. Banerjee, and Y.-W. Chang, “An efficient and effective analytical placer for fpgas,” in Proceedings of the 50th Annual Design Automation Conference, ser. DAC ’13. New York, NY, USA: ACM, 2013, pp. 10:1–10:6.

[6] D. Chen, J. Cong, and P. Pan, “Fpga design automation: A survey,” Found. Trends Electron. Des. Autom., vol. 1, no. 3, pp. 139–169, Jan. 2006.

[7] G.-J. Nam and J. Cong, Modern Circuit Placement: Best Practices and Results, 1st ed. Springer Publishing Company, Incorporated, 2007.

[8] C.-C. Chang, J. Cong, M. Romesis, and M. Xie, “Optimality and scalability study of existing placement algorithms,” Trans. Comp.-Aided Des. Integ. Cir. Sys., vol. 23, no. 4, pp. 537–549, Nov. 2006.

[9] J. Cong, M. Romesis, J. Shinnerl, K. Sze, and M. Xie, “Locality and utilization in placement suboptimality,” in Modern Circuit Placement, ser. Series on Integrated Circuits and Systems, G.-J. Nam and J. Cong, Eds. Springer US, 2007, pp. 13–36.

[10] D. A. Papa, S. N. Adya, and I. L. Markov, “Constructive benchmarking for placement,” in Proceedings of the 14th ACM Great Lakes Symposium on VLSI, ser. GLSVLSI ’04. New York, NY, USA: ACM, 2004, pp. 113–118.

[11] S. I. Ward, D. A. Papa, Z. Li, C. N. Sze, C. J. Alpert, and E. Swartzlander, “Quantifying academic placer performance
on custom designs,” in Proceedings of the 2011 International Symposium on Physical Design, ser. ISPD ’11. New York, NY, USA: ACM, 2011, pp. 91–98. 

[12] A. Cooperation, “Quartus ii handbook version 12.1,” in Quartus II Handbook, 2012.

[13] J. Lam and J.-M. Delosme, “Performance of a new annealing schedule,” in Proceedings of the 25th ACM/IEEE Design Automation Conference, ser. DAC ’88. Los Alamitos, CA, USA: IEEE Computer Society Press, 1988, pp. 306–311. 

[14] V. Betz, J. Rose, and A. Marquardt, Eds., Architecture and CAD for Deep-Submicron FPGAs. Norwell, MA, USA: Kluwer Academic Publishers, 1999.
