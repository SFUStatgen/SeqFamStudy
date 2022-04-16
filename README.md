# SeqFamStudy
Simulated Sequencing Study of Lymphoid Cancer Families

This repository contains the RMarkdown files and other scripts to generate the simulated data for an exome-sequencing study of 150 families ascertained to contain at least four members affected with lymphoid cancer.  The following flow chart explains our work flow.

![Flow Chart](https://github.com/SFUStatgen/SeqFamStudy/blob/main/SLiM/Flow%20Chart.png)

Each coloured box in the chart is a major step in our data simulation. We have created three folders to represent each box. They are:

1. SLiM (green box) - materials for simulating the population-level sequence data in SLiM.
2. SimRVped (blue box) - materials for simulating the 150 families containing four or more individuals affected with lymphoid cancer.
3. SimRVseq (orange box) - materials for generating the sequence data of affected individuals and their relatives in the 150 families from step 2, given that they come from the population in step 1.

This repository is archived in Zenodo at https://zenodo.org/record/6347546.
