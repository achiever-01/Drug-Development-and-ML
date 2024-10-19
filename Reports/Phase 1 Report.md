**DOCKING AND PIPELINE IMPLEMENTATION**

**Authors (@slack):** Rukayat Jimoh (@Justjpearl), Ameenat Oloko (@Ameenat), Popoola Opeyemi Emmanuel (@Emmanuel), Adesina Damilola Victoria (@Victoria63) and Deborah Abolarinwa (@Achiever01).

**Phase 1: Docking Implementation**

**Introduction**

Renal cancer is the predominant malignant tumor of the kidney, originating in the kidney cells (Eisenberger _et al.,_ 1999). Cyclin-Dependent Kinase 1 (CDK1) protein, which plays a crucial role in cell cycle regulation, is a promising target for cancer treatment (Li _et al.,_ 2022). CDK1 overexpression and hyperactivation correlate with the uncontrolled proliferation of renal cancer cells; thus, inhibiting this protein may induce cell cycle arrest, offering a potential therapeutic advantage (Sager _et al.,_ 2022).

**Panax Ginseng**

_Panax ginseng_ is a medicinal plant recognized for its bioactive compounds, which exhibit antitumor, anti-inflammatory, and antioxidant effects in multiple cancer studies (Jakaria _et al.,_ 2018; Meng _et al.,_ 2024). This study investigates the therapeutic potential of _Panax ginseng_ in renal cancer treatment via its interaction with CDK1 proteins and evaluates the molecular docking of phytochemicals derived from _Panax ginseng_ with CDK1 to determine their potential as inhibitors of CDK1 in the treatment of renal cancer.

**Methodology**

A.    Protein Identification

Cyclin-dependent Kinase 1 (CDK1) has been found on the Human Protein Atlas as a marker of poor prognosis in renal cancer. The protein structure, identified by PDB ID **6GU6** (a CDK1/Cks2 complex complexed with Dinaciclib), was obtained from the RCSB Protein Data Bank.

![6GU6 Protein](https://github.com/user-attachments/assets/a58c0c58-7ea5-4dbd-beed-c5977f96917e)

**Fig 1: 6GU6 Protein**


B.    Active Sites of the Protein

The protein's active sites were identified using the CASTp computational software, revealing the sequence Methionine, Tyrosine, Threonine, Lysine, Isoleucine, Glycine, Glutamic acid, Arginine, Histidine, Glutamine, Leucine, Serine, Valine, Proline, Phenylanine, Aspartatic acid, and Alanine. Their visualization was conducted using the PyMol software.

![Active Sites of 6GU6](https://github.com/user-attachments/assets/8b4aa489-c0e1-4f25-be18-f091af5a7fc8)


**Fig 2: Active Sites of the 6GU6 Protein**


C.    Phytochemical Library

A total of 52 phytochemicals from the plant were identified through published literature, and their 2D structures were obtained in SDF format from the PubChem library. The structures were subsequently converted into 3D formats (PDB) utilizing the Open Babel website.

D.    Docking

MGL Tools, Autodock 4, and Autodock Vina were acquired and used for the molecular docking of the protein and phytochemicals. Autodock 4 was used to prepare and convert the protein from PDB to PDBQT format by removing the Dinaciclib ligand (1QK) and water molecules, checking and repairing missing atoms, and adding polar hydrogens and Kollman charges. The three-dimensional structures of the phytochemicals were generated and converted into PDBQT format. A grid box was generated via Autodock 4. Autodock Vina was then used for docking the protein with the phytochemicals, using an energy range of 4 and an exhaustiveness of 8. The docking findings yielded 9 binding affinities for each phytochemical, with the greatest affinity recorded first. The result and protein conformation were visualised via PyMOL.

E.    Results

The 52 phytochemicals were docked with the 6GU6 protein and visualised using PyMOL; however, only 10 with the highest affinity were selected for this result.

   

    
![Ginsenoside F2 Visualisation](https://github.com/user-attachments/assets/736dd9b0-6b48-44b0-aa63-61f1cfff3fc3)

![Ginsenoside F2 affinity results](https://github.com/user-attachments/assets/f0127673-46fe-4584-bdad-fe9d5c2faf50)


**Fig 3:  Ginsenoside F2**

    
![Ginsenoside Rg3 Visualisation](https://github.com/user-attachments/assets/2e1b438a-9193-4f8a-89b4-050c612e68fe)

![Ginsenoside F2 affinity results](https://github.com/user-attachments/assets/f0127673-46fe-4584-bdad-fe9d5c2faf50)

**Fig 4: Ginsenoside Rg3**

  
![Apigenin Vis](https://github.com/user-attachments/assets/b0dfdf92-dacd-4903-bcc7-e2d99174fd2d)

![Apigenin Affinity](https://github.com/user-attachments/assets/604089a7-20f9-4ff9-b72c-969bf18fa50e)

**Fig 5: Apigenin**

 
![Epicatechin Vis](https://github.com/user-attachments/assets/87942584-4aaa-43ba-8065-c4519bf8f545)

![Epicatechin Affinity](https://github.com/user-attachments/assets/d0692be4-905e-441d-bb60-6f8fd25fba4c)

**Fig 6:  Epicatechin**

    
![Kaempferol Vis](https://github.com/user-attachments/assets/8873ef22-dd3e-419f-aa0c-45753a691615)

![Kaempferol Aff](https://github.com/user-attachments/assets/ac106ac5-2e3b-4878-84f6-5ff95d8ecfe9)

**Fig 7: Kaempferol**

  
![Quercitrin Vis](https://github.com/user-attachments/assets/e73ce5a1-4a8f-4829-a16c-6c2d2bcb4cd4)

![Quercitrin Aff](https://github.com/user-attachments/assets/6acf11d2-10d9-4f88-b0f8-f4f635b47fc2)


**Fig 8: Quercitrin**

   
![Guanosine Vis](https://github.com/user-attachments/assets/9b75ab2b-97f9-4313-817b-191055c45d2c)

![Guanosine Aff](https://github.com/user-attachments/assets/4410b0ce-2b5b-4f5a-a1a1-e8b9d4e420d5)

**Fig 9: Guanosine**


![Menadione Vis](https://github.com/user-attachments/assets/c81c3c62-5125-44be-a997-743fba14ebaa)

![Menadione Aff](https://github.com/user-attachments/assets/e65f88f7-5013-42c3-ae55-b526d226507c)

**Fig 10:  Menadione**


![Indole-3-acetic acid Vis](https://github.com/user-attachments/assets/7d15df94-050d-4d65-9478-7eb686d4acde)

![Indole-3-acetic acid Aff](https://github.com/user-attachments/assets/62fd07db-f806-4452-8b97-cd10ed44f9e3)


**Fig 11: Indole-3-acetic acid**

    
![p-coumaric acid vis](https://github.com/user-attachments/assets/0cc3e16e-02c1-4525-a1d2-f02060878358)

![p-coumaric acid aff](https://github.com/user-attachments/assets/086240e9-0398-4d42-9d13-06375b969d24)

**Fig 12: p-coumaric acid**

**Conclusion**

Docking analysis demonstrated that Ginsenoside F2 and Ginsenoside Rg3 exhibit the highest binding affinities to the 6GU6 protein, particularly at its active sites. Ginsenoside F2 displayed the highest potential as a CDK1 inhibitor in renal cancer, with a binding affinity of -12.5 kcal/mol.


**References**

1.     Chen, J., Yuan, Y., Ran, X., Guo, N., & Dou, D. (2018). Metabolomics analysis based on a UPLC-Q-TOF-MS metabolomics approach to compare Lin-Xia-Shan-Shen and garden ginseng. RSC Advances, 8(53), 30616-30623.

2.     Chung, I. M., Lim, J. J., Ahn, M. S., Jeong, H. N., An, T. J., & Kim, S. H. (2016). Comparative phenolic compound profiles and antioxidative activity of the fruit, leaves, and roots of Korean ginseng (Panax ginseng Meyer) according to cultivation years. Journal of Ginseng Research, 40(1), 68-75.

3.     Eisenberger, C. F., Schoenberg, M., Enger, C., Hortopan, S., Shah, S., Chow, N. H., ... & Sidransky, D. (1999). Diagnosis of renal cancer by molecular urinalysis. Journal of the National Cancer Institute, 91(23), 2028-2032.

4.     Jakaria, M., Haque, M. E., Kim, J., Cho, D. Y., Kim, I. S., & Choi, D. K. (2018). Active ginseng components in cognitive impairment: Therapeutic potential and prospects for delivery and clinical study. _Oncotarget_, _9_(71), 33601.

5.     Kim, J. S. (2016). Investigation of phenolic, flavonoid, and vitamin contents in different parts of Korean ginseng (Panax ginseng C.A. Meyer). Preventive Nutrition and Food Science, 21(3), 263-270.

6.     Kim, J. S. (2016). Investigation of phenolic, flavonoid, and vitamin contents in different parts of Korean ginseng (Panax ginseng C.A. Meyer). Preventive Nutrition and Food Science, 21(3), 263-270.

7.     Kim, K., Kim, M. H., Kang, J. I., Baek, J. I., Jeon, B. M., Kim, H. M., ... & Jeong, W. I. (2024). Ginsenoside F2 restrains hepatic steatosis and inflammation by altering the binding affinity of liver X receptor coregulators. Journal of Ginseng Research, 48(1), 89-97.

8.     Kim, S. H., Kim, S. Y., & Choi, H. K. (2018). Lipids in ginseng (Panax ginseng) and their analysis. Natural Product Sciences, 24(1), 1-12.

9.     Kim, S. N., Ha, Y. W., Shin, H., Son, S. H., Wu, S. J., & Kim, Y. S. (2007). Simultaneous quantification of 14 ginsenosides in Panax ginseng CA Meyer (Korean red ginseng) by HPLC-ELSD and its application to quality control. Journal of Pharmaceutical and Biomedical Analysis, 45(1), 164-170.

10.  Lee, D. G., Lee, A. Y., Kim, K. T., Cho, E. J., & Lee, S. (2015). Novel dammarane-type triterpene saponins from Panax ginseng root. Chemical and Pharmaceutical Bulletin, 63(11), 927-934.

11.  Lee, D. G., Lee, J., Kim, K. T., Lee, S. W., Kim, Y. O., Cho, I. H., Kim, H. J., Park, C. G., & Lee, S. (2018). High-performance liquid chromatography analysis of phytosterols in Panax ginseng root grown under different conditions. Journal of Ginseng Research, 42(1), 16-20.

12.  Lee, J. W., Choi, B. R., Kim, Y. C., Choi, D. J., Lee, Y. S., Kim, G. S., ... & Lee, D. Y. (2017). Comprehensive profiling and quantification of ginsenosides in the root, stem, leaf, and berry of Panax ginseng by UPLC-QTOF/MS. Molecules, 22(12), 2147.

13.  Li, H., Zheng, P., Li, Z., Han, Q., Zhou, B., Wang, X., & Wang, K. (2022). NCAPG promotes the proliferation of renal clear cell carcinoma via mediating with CDK1. Disease markers, 2022(1), 6758595.

14.  Liu, J., Jiang, R., Zhou, J., Xu, X., Sun, Z., Li, J., Chen, X., Li, Z., Yan, X., Zhao, D., Zheng, Z., & Sun, L. (2021). Salicylic acid in ginseng root alleviates skin hyperpigmentation disorders by inhibiting melanogenesis and melanosome transport. European Journal of Pharmacology, 910, 174458.

15.  Liu, J., Liu, Y., Wang, Y., Abozeid, A., Zu, Y. G., & Tang, Z. H. (2017). The integration of GC–MS and LC–MS to assay the metabolomics profiling in Panax ginseng and Panax quinquefolius reveals a tissue-and species-specific connectivity of primary metabolites and ginsenosides accumulation. Journal of Pharmaceutical and Biomedical Analysis, 135, 176-185.

16.  Meng, F., & Li, Z. (2024). Characterization, cytotoxicity and anti-human renal cell carcinoma efficacies of copper nanoparticles green-synthesized by Panax ginseng. Inorganic Chemistry Communications, 162, 112263.

17.  Park, T. Y., Hong, M., Sung, H., Kim, S., & Suk, K. T. (2017). Effect of Korean red ginseng in chronic liver disease. Journal of Ginseng Research, 41(4), 450-455.

18.  Ratan, Z. A., Haidere, M. F., Hong, Y. H., Park, S. H., Lee, J. O., Lee, J., & Cho, J. Y. (2021). Pharmacological potential of ginseng and its major component ginsenosides. Journal of ginseng research, 45(2), 199-210.

19.  Sager, R. A., Backe, S. J., Ahanin, E., Smith, G., Nsouli, I., Woodford, M. R., ... & Mollapour, M. (2022). Therapeutic potential of CDK4/6 inhibitors in renal cell carcinoma. Nature Reviews Urology, 19(5), 305-320.

20.  Sharma, A., & Lee, H. J. (2020). Ginsenoside compound K: insights into recent studies on pharmacokinetics and health-promoting activities. Biomolecules, 10(7), 1028.

21.  Shin, B. K., Kwon, S. W., & Park, J. H. (2015). Chemical diversity of ginseng saponins from Panax ginseng. Journal of ginseng research, 39(4), 287-298.

22.  Yang, Y., Ju, Z., Yang, Y., Zhang, Y., Yang, L., & Wang, Z. (2021). Phytochemical analysis of Panax species: a review. Journal of Ginseng Research, 45(1), 1-21.
