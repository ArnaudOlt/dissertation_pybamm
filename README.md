# Dissertation Arnaud Oltramare
Scripts to reproduce the results of the dissertation.

# How to use the code?
All notebooks include a Google Colab link. The following files can be run directly by clicking the Google Colab link:

```1_model_validation.ipynb```, ```2_1_anode_potential_validation.ipynb```, ```2_2_anode_potential_at_three_temp.ipynb```, ```3_1_reversible_li_plt_loss.ipynb```, ```4_1_temperature_degradation_standard_cycling_vs_lunana_cycling.ipynb```

The following files requires Google Colab Pro with enough available RAM:

```3_2_permanent_li_plt_loss_standa```, ```4_2_temp_cap_loss_over_throughput_time.ipynb```,```5_1_SOC_degradation.ipynb```, ```5_2_load_plot_SOC.ipynb```

Make sure to connect your Google Drive in order to save simulations.

# Support
I thank Valentin Sulzer, Michael Schimpe and Michael O'Kane for their support and guidance.\
I thank Bjarte Steinsund for providing the code used in ref. [15]. The code in ```5_1_SOC_degradation.ipynb``` is largely based on that code.\
I thank Ferran Brosa Planella for his openly available code in ref. [16] that has been used to compare the SPMe vs DFN model.

# References
[1] Weilong Ai, Ludwig Kraft, Johannes Sturm, Andreas Jossen, and Billy Wu. Electrochemical thermal-mechanical modelling of stress inhomogeneity in lithium-ion pouch cells. Journal of The Electrochemical Society, 167(1):013512, 2019. doi:10.1149/2.0122001JES.\
[2] Joel A. E. Andersson, Joris Gillis, Greg Horn, James B. Rawlings, and Moritz Diehl. CasADi – A software framework for nonlinear optimization and optimal control. Mathematical Programming Computation, 11(1):1–36, 2019. doi:10.1007/s12532-018-0139-4.\
[3] Chang-Hui Chen, Ferran Brosa Planella, Kieran O'Regan, Dominika Gastol, W. Dhammika Widanage, and Emma Kendrick. Development of Experimental Techniques for Parameterization of Multi-scale Lithium-ion Battery Models. Journal of The Electrochemical Society, 167(8):080534, 2020. doi:10.1149/1945-7111/ab9050.\
[4] Rutooj Deshpande, Mark Verbrugge, Yang-Tse Cheng, John Wang, and Ping Liu. Battery cycle life prediction with coupled chemical degradation and fatigue mechanics. Journal of the Electrochemical Society, 159(10):A1730, 2012. doi:10.1149/2.049210jes.\
[5] Marc Doyle, Thomas F. Fuller, and John Newman. Modeling of galvanostatic charge and discharge of the lithium/polymer/insertion cell. Journal of the Electrochemical society, 140(6):1526–1533, 1993. doi:10.1149/1.2221597.\
[6] Charles R. Harris, K. Jarrod Millman, Stéfan J. van der Walt, Ralf Gommers, Pauli Virtanen, David Cournapeau, Eric Wieser, Julian Taylor, Sebastian Berg, Nathaniel J. Smith, and others. Array programming with NumPy. Nature, 585(7825):357–362, 2020. doi:10.1038/s41586-020-2649-2.\
[7] Scott G. Marquis. Long-term degradation of lithium-ion batteries. PhD thesis, University of Oxford, 2020.\
[8] Peyman Mohtat, Suhak Lee, Jason B Siegel, and Anna G Stefanopoulou. Towards better estimability of electrode-specific state of health: decoding the cell expansion. Journal of Power Sources, 427:101–111, 2019.\
[9] Simon E. J. O'Kane, Ian D. Campbell, Mohamed W. J. Marzook, Gregory J. Offer, and Monica Marinescu. Physical origin of the differential voltage minimum associated with lithium plating in li-ion batteries. Journal of The Electrochemical Society, 167(9):090540, may 2020. URL: https://doi.org/10.1149/1945-7111/ab90ac, doi:10.1149/1945-7111/ab90ac.\
[10] Simon E. J. O'Kane, Weilong Ai, Ganesh Madabattula, Diego Alonso-Alvarez, Robert Timms, Valentin Sulzer, Jacqueline Sophie Edge, Billy Wu, Gregory J. Offer, and Monica Marinescu. Lithium-ion battery degradation: how to model it. Phys. Chem. Chem. Phys., 24:7909-7922, 2022. URL: http://dx.doi.org/10.1039/D2CP00417H, doi:10.1039/D2CP00417H.\
[11] Jorn M. Reniers, Grietus Mulder, and David A. Howey. Review and performance comparison of mechanical-chemical degradation models for lithium-ion batteries. Journal of The Electrochemical Society, 166(14):A3189, 2019. doi:10.1149/2.0281914jes.\
[12] Valentin Sulzer, Scott G. Marquis, Robert Timms, Martin Robinson, and S. Jon Chapman. Python Battery Mathematical Modelling (PyBaMM). Journal of Open Research Software, 9(1):14, 2021. doi:10.5334/jors.309.\
[13] Pauli Virtanen, Ralf Gommers, Travis E. Oliphant, Matt Haberland, Tyler Reddy, David Cournapeau, Evgeni Burovski, Pearu Peterson, Warren Weckesser, Jonathan Bright, and others. SciPy 1.0: fundamental algorithms for scientific computing in Python. Nature Methods, 17(3):261–272, 2020. doi:10.1038/s41592-019-0686-2.\
[14] Andrew Weng, Jason B Siegel, and Anna Stefanopoulou. Differential voltage analysis for battery manufacturing process control. arXiv preprint arXiv:2303.07088, 2023.\
[15] R. H. Kidane, J. Myklebust and B. Steinsund, ‘LiB Ageing Mechanisms and Energy Storage Replacement/Expansion in Marine Vessels’, 2022. [Online]. Available: https://ntnuopen. ntnu.no/ntnu-xmlui/handle/11250/3001891.\
[16] F. Brosa Planella, W. Ai, A. M. Boyce et al., ‘A continuum of physics-based lithium-ion battery models reviewed’, Progress in Energy, vol. 4, no. 4, p. 042 003, Jul. 2022, issn: 2516-1083. doi:10.1088/2516-1083/AC7D31 [Online]. Available: https://iopscience.iop.org/article/10.1088/2516- 1083/ac7d31https://iopscience.iop.org/article/10.1088/25161083/ac7d31/meta. \
[17] Scott G. Marquis, Valentin Sulzer, Robert Timms, Colin P. Please, and S. Jon Chapman. An asymptotic derivation of a single particle model with electrolyte. Journal of The Electrochemical Society, 166(15):A3693–A3706, 2019. doi:10.1149/2.0341915jes.\
[18] Dongsheng Ren, Kandler Smith, Dongxu Guo, Xuebing Han, Xuning Feng, Languang Lu, and Minggao Ouyang. Investigation of lithium plating-stripping process in li-ion batteries at low temperature using an electrochemical model. Journal of the Electrochemistry Society, 165:A2167-A2178, 2018. doi:10.1149/2.0661810jes.



