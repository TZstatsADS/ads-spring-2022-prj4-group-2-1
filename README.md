# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Spring 2022

+ Team # 2
+ Projec title: Learning fair representations (LFR) vs. Fairness Beyond Disparate Treatment & Disparate Impact: Learning Classification without Disparate Mistreatment (DM and DM-sen)
+ Team members
	+ Cai, Guosheng
	+ E, Daoyang
	+ Song, Peixuan
	+ Wang, Kaimin
	+ Xu, Rong
+ Project summary: In this project, our group was assigned to implement two different machine learning fairness algorithms that could handle sensitive attributes(LFR, DM and DM-sen) and compare their performances. The final results: The testing accuracy for overall LFR model is 52%, but test accuracy for nonprotected group using LFR drops to 46%. By contrast, the testing accuracy using DM and DM-sen all goes around 65%.  The project conclusion: There is an apparent decrease in accuracy between DM and DM-sen model and the LFR model. This makes sense because fairness measure "cleans" the data to achieve fairness while DM and DM-sen does not remove information from the data.
	
**Contribution statement**: The group was initially built into two teams. Kaimin and Peixuan worked on the LFR algorithm. Kaimin preprocessed the data, built the LFR model, implemented the optimization using sklearn, defined and ran the model selection process, and defined evaluation and testing steps. Peixuan did the research part, debugged and drew up an explanation of the algorithm. Rong and Guosheng worked on the DM and DM-sen algorithm. Rong first preprocessed the data, built up the logistic regression and SVM version of DM and DM-sen algorithm. Guosheng further analyzed the research paper to write the explanation of the algorithm and helped on coding and debugging. Daoyang started the main framework for the final report and the presentation preparitions, wrote the evaluation and the comparison of results. All team members were involved in the different algorithms equally and helped to get the final conclusion. Kaimin initially updated the README and was later developed by Daoyang. Daoyang presented the project.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
