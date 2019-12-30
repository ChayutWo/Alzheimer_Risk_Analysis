# Alzheimer Risk Analysis

In this project, we give comprehensive analysis on Alzheimer’s disease data. A model to classify diﬀerent Alzheimer’s phases (Normal, Mild Cognitive Impairment, and Dementia) is developed using proportional odds ratio technique. Risk score formula is proposed and shown that people who had Mild Cognitive Impairment and progressed to Dementia within a year, on average, had higher score. Finally, a regression model to explain variability in Hippocampal volume of patients is discussed. 

## Objectives

1. To build statistical models based on simple neuropsychological tests that could be administered online to predict Alzheimer’s phases in patients, and compare their predictive capability with other methods proposed within research community. 
2. To construct a risk score metric using the model in the ﬁrst section in capturing the potential conversion to more severe states of Alzheimer’s disease in the future. 
3. To investigate the capability of these basic tests in estimating some of the biomarkers that have been believed to play major roles in the progression of the disease.

## Dataset

Data used in the preparation of this article were obtained from the Alzheimer’s Disease Neuroimaging Initiative (ADNI) database (adni.loni.usc.edu). The ADNI was launched in 2003 as a public-private partnership, led by Principal Investigator Michael W. Weiner, MD. The primary goal of ADNI has been to test whether serial magnetic resonance imaging (MRI), positron emission tomography (PET), other biological markers, and clinical and neuropsychological assessment can be combined to measure the progression of mild cognitive impairment (MCI) and early Alzheimer’s disease (AD). For up-to-date information, see www.adni-info.org.

## Software and analytical approaches

All analysis programming is done using R. The statistical techniques covered in this study includes proportional odds model for classification tasks and generalized linear model (GLM) for regression tasks. For details on R packages, please look at Rmd file.

## File description


## Authors

* **Chayut Wongkamthong, Duke University** - *Initial work* 

## Acknowledgments

Data collection and sharing for this project was funded by the Alzheimer's Disease Neuroimaging Initiative (ADNI) (National Institutes of Health Grant U01 AG024904) and DOD ADNI (Department of Defense award number W81XWH-12-2-0012). ADNI is funded by the National Institute on Aging, the National Institute of Biomedical Imaging and Bioengineering, and through generous contributions from the following: AbbVie, Alzheimer’s Association; Alzheimer’s Drug Discovery Foundation; Araclon Biotech; BioClinica, Inc.; Biogen; Bristol-Myers Squibb Company; CereSpir, Inc.; Cogstate; Eisai Inc.; Elan Pharmaceuticals, Inc.; Eli Lilly and Company; EuroImmun; F. Hoffmann-La Roche Ltd and its affiliated company Genentech, Inc.; Fujirebio; GE Healthcare; IXICO Ltd.; Janssen Alzheimer Immunotherapy Research & Development, LLC.; Johnson & Johnson Pharmaceutical Research & Development LLC.; Lumosity; Lundbeck; Merck & Co., Inc.; Meso Scale Diagnostics, LLC.; NeuroRx Research; Neurotrack Technologies; Novartis Pharmaceuticals Corporation; Pfizer Inc.; Piramal Imaging; Servier; Takeda Pharmaceutical Company; and Transition Therapeutics. The Canadian Institutes of Health Research is providing funds to support ADNI clinical sites in Canada. Private sector contributions are facilitated by the Foundation for the National Institutes of Health (www.fnih.org). The grantee organization is the Northern California Institute for Research and Education, and the study is coordinated by the Alzheimer’s Therapeutic Research Institute at the University of Southern California. ADNI data are disseminated by the Laboratory for Neuro Imaging at the University of Southern California.

## References

[1] Pagel, M., Becker, J., & Coppel, D.B. (1985). Loss of control, self-blame, and depression: an investigation of spouse caregivers of Alzheimer’s disease patients. Journal of abnormal psychology, 94 2, 169-82 .
[2] The National Institute on Aging’s Alzheimer’s and related Dementias Education and Referral (ADEAR) Center
[3] Petersen RC, Smith GE, Waring SC, Ivnik RJ, Tangalos EG, Kokmen E. Mild Cognitive Impairment: Clinical Characterization and Outcome. Arch Neurol. 1999;56(3):303–308.
[4] Petersen R. C. (2009). Early diagnosis of Alzheimer’s disease: is MCI too late?. Current Alzheimer research, 6(4), 324–330.
[5] Vanderstichele, Hugo & Bibl, Mirko & Engelborghs, Sebastiaan & Le Bastard, Nathalie & Lewczuk, Piotr & Molinuevo, Jose & Parnetti, Lucilla & Perret-Liaudet, Armand & Shaw, Leslie & Teunissen, Charlotte & Wouters, Dirk & Blennow, Kaj. (2011). The clinical use of cerebrospinal fluid biomarker testing for Alzheimer’s disease diagnosis: A consensus paper from the Alzheimer’s Biomarkers Standardization Initiative. Alzheimer’s & dementia : the journal of the Alzheimer’s Association. 8. 65-73.
[6] Jack, C. R., Jr, Knopman, D. S., Jagust, W. J., Shaw, L. M., Aisen, P. S., Weiner, M. W., . . . Trojanowski, J. Q. (2010). Hypothetical model of dynamic biomarkers of the Alzheimer’s pathological cascade. The Lancet. Neurology, 9(1), 119–128.
[7] http://adni.loni.usc.edu/about/adni1/
[8] Matloubi S, Mohammadzadeh A, Jafari Z, Akbarzadeh Baghban A. Effect of background music on auditoryverbal memory performance. Audiology. 2014:0-.
[9] Patel, T., & Kurdi, M. S. (2015). A comparative study between oral melatonin and oral midazolam on preoperative anxiety, cognitive, and psychomotor functions. Journal of anaesthesiology, clinical pharmacology, 31(1), 37–43.
[10] Li, Fan & Liu, Manhua. (2018). Alzheimer’s Disease Diagnosis Based on Multiple Cluster Dense Convo- lutional Networks. Computerized Medical Imaging and Graphics. 70. 10.1016/j.compmedimag.2018.09.009.
[11] Andres Ortiz, F. Lozano, Juan M. Górriz*, Javier Ramírez, Francisco J. Martínez Murcia and for the Alzheimer’s Disease Neuroimaging Initiative, “Discriminative Sparse Features for Alzheimer’s Disease Diagnosis Using Multimodal Image Data”, Current Alzheimer Research (2018) 15: 67.
[12] Cheng, B., Liu, M., Suk, H. I., Shen, D., Zhang, D., & Alzheimer’s Disease Neuroimaging Initiative (2015). Multimodal manifold-regularized transfer learning for MCI conversion prediction. Brain imaging and behavior, 9(4), 913–926.
[13] Gross, A. L., Mungas, D. M., Leoutsakos, J. S., Albert, M. S., & Jones, R. N. (2016). Alzheimer’s disease severity, objectively determined and measured. Alzheimer’s & dementia (Amsterdam, Netherlands), 4, 159–168.
[14] Pfeffer RI, Kurosaki TT, Harrah CH, Jr, et al. Measurement of functional activities in older adults in the community. J Gerontol. 1982;37:323–329.
[15] Chen, Y., Denny, K. G., Harvey, D., Farias, S. T., Mungas, D., DeCarli, C., & Beckett, L. (2017). Progression from normal cognition to mild cognitive impairment in a diverse clinic-based and community-based elderly cohort. Alzheimer’s & dementia : the journal of the Alzheimer’s Association, 13(4), 399–405.
[16] Murphy, M. P., & LeVine, H., 3rd (2010). Alzheimer’s disease and the amyloid-beta peptide. Journal of Alzheimer’s disease : JAD, 19(1), 311–323.
[17] http://adni.loni.usc.edu/study-design/#background-container
